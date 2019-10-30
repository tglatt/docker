FROM registry.gitlab.factory.social.gouv.fr/socialgouv/docker/curl:0.9.1 AS kustomize-image

#

WORKDIR /tmp

RUN set -ex \
  && VERSION="3.3.0" \
  && SHA256SUMS="4b49e1bbdb09851f11bb81081bfffddc7d4ad5f99b4be7ef378f6e3cf98d42b6" \
  && CDN="https://github.com/kubernetes-sigs/kustomize/releases/download" \
  && PACKAGE="kustomize_v${VERSION}_linux_amd64.tar.gz" \
  && curl -L --output /tmp/${PACKAGE} ${CDN}/kustomize%2Fv${VERSION}/${PACKAGE} \
  && echo "${SHA256SUMS}  /tmp/${PACKAGE}" | sha256sum -c \
  && tar xzf /tmp/${PACKAGE} \
  && mv /tmp/kustomize /usr/local/bin/kustomize \
  && chmod +x /usr/local/bin/kustomize

#

FROM registry.gitlab.factory.social.gouv.fr/socialgouv/docker/helm:0.9.1 AS helm-image
FROM alpine:3.10

#

COPY --from=helm-image /usr/bin/helm /usr/bin/helm
COPY --from=helm-image /usr/local/bin/kubectl /usr/local/bin/kubectl
COPY --from=kustomize-image /usr/local/bin/kustomize /usr/local/bin/kustomize

#

ENTRYPOINT ["/usr/local/bin/kustomize"]
