FROM postgres:12.1-alpine

COPY ./bin /bin

ENTRYPOINT ["/bin/wait-for-postgres"]
