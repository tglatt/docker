# [0.21.0](https://github.com/SocialGouv/docker/compare/v0.20.0...v0.21.0) (2019-12-31)


### Features

* **deps:** update alpine docker tag ([015cea2](https://github.com/SocialGouv/docker/commit/015cea2d2ba070330b3bf60c16458e8b85292ee4))

# [0.20.0](https://github.com/SocialGouv/docker/compare/v0.19.0...v0.20.0) (2019-12-20)


### Bug Fixes

* **k8s-object-cleaner:** use /usr/bin/env shebang ([cec7151](https://github.com/SocialGouv/docker/commit/cec7151961539fdc874511ec208db25d00aa3e38))
* **k8s-object-cleaner:** use sha1sum instead of shasum ([8db9485](https://github.com/SocialGouv/docker/commit/8db94852c4b6ad5a2d50c06f2752c977d3aff9f6))


### Features

* **k8s-object-cleaner:** add a k8s object cleaner ([#64](https://github.com/SocialGouv/docker/issues/64)) ([5be8a41](https://github.com/SocialGouv/docker/commit/5be8a410dc38a6935aef4b4e29f0872663221f06))

# [0.19.0](https://github.com/SocialGouv/docker/compare/v0.18.0...v0.19.0) (2019-12-14)


### Features

* **kubectl:** update kubectl to 0.17.0 ([#62](https://github.com/SocialGouv/docker/issues/62)) ([107de13](https://github.com/SocialGouv/docker/commit/107de133f50a6d42977f1a43c5e517403618616e))
* **nginx4spa:** configurable PORT ([#61](https://github.com/SocialGouv/docker/issues/61)) ([476fe97](https://github.com/SocialGouv/docker/commit/476fe97e5b56de81a1a3d8d031754e99938387f7))
* **wait-for-postgres:** add wait-for-postgres image ([#65](https://github.com/SocialGouv/docker/issues/65)) ([66be586](https://github.com/SocialGouv/docker/commit/66be5864a53ccf162d6414af875881b2e4c3063d)), closes [#47](https://github.com/SocialGouv/docker/issues/47)

# [0.18.0](https://github.com/SocialGouv/docker/compare/v0.17.0...v0.18.0) (2019-12-05)


### Features

* **puppetteer:** add common puppetteer image ([#53](https://github.com/SocialGouv/docker/issues/53)) ([d953973](https://github.com/SocialGouv/docker/commit/d9539731e68ca63b02bc7389247fd58a74da0ff9))


### Reverts

* Revert "ci(gitlab): allow some job to fail due to missing image" ([38a57bb](https://github.com/SocialGouv/docker/commit/38a57bb758730322ced6199b2dc1e3ab077a438a))

# [0.17.0](https://github.com/SocialGouv/docker/compare/v0.16.0...v0.17.0) (2019-12-05)


### Features

* use partial pin to master version glob ([#55](https://github.com/SocialGouv/docker/issues/55)) ([28e9317](https://github.com/SocialGouv/docker/commit/28e9317d0d538c33d8ff5aac4cada653d7afd9a0))

# [0.16.0](https://github.com/SocialGouv/docker/compare/v0.15.0...v0.16.0) (2019-12-03)


### Features

* **infra-ansible-ci:** add ansible[azure] to infra-ansible-ci ([#52](https://github.com/SocialGouv/docker/issues/52)) ([1fee81e](https://github.com/SocialGouv/docker/commit/1fee81ef172a5769e4aee3c1a1bfa48010537942))

# [0.15.0](https://github.com/SocialGouv/docker/compare/v0.14.0...v0.15.0) (2019-11-25)


### Features

* **infra-ansible-ci:** add yq tools ([#46](https://github.com/SocialGouv/docker/issues/46)) ([9851727](https://github.com/SocialGouv/docker/commit/9851727779f21d8f8056ff0154fc7db203399d27))

# [0.14.0](https://github.com/SocialGouv/docker/compare/v0.13.0...v0.14.0) (2019-11-25)


### Features

* **k8s-ns-killer:** update git to 2.24.0-r0 ([a02c364](https://github.com/SocialGouv/docker/commit/a02c3644668cd4c65ee881218b20cc19ba7f65f7))

# [0.13.0](https://github.com/SocialGouv/docker/compare/v0.12.0...v0.13.0) (2019-11-18)


### Bug Fixes

* **helm:** use bash=5.0.0-r0 ([0a6556a](https://github.com/SocialGouv/docker/commit/0a6556a256bbf9e3ac78bbd3e65bb4a4f1d68d51))
* typofix ([#38](https://github.com/SocialGouv/docker/issues/38)) ([b66d4a2](https://github.com/SocialGouv/docker/commit/b66d4a2d895a85c1a5c5574f446574869cf80c52))


### Features

* add hadolint ([#40](https://github.com/SocialGouv/docker/issues/40)) ([7bc8b83](https://github.com/SocialGouv/docker/commit/7bc8b830604e39892c24d35c5a168704e5e0913c))

# [0.12.0](https://github.com/SocialGouv/docker/compare/v0.11.2...v0.12.0) (2019-11-12)


### Features

* **nginx4spa:** add spa nginx image ([#33](https://github.com/SocialGouv/docker/issues/33)) ([1bfd078](https://github.com/SocialGouv/docker/commit/1bfd078938823f924d7289653ce75a210de46cde))
* **spa-nginx:** add spa nginx image ([#31](https://github.com/SocialGouv/docker/issues/31)) ([f642a9c](https://github.com/SocialGouv/docker/commit/f642a9c9ff3f8ad49385cddd4b61c5d1e4996cc2))

## [0.11.2](https://github.com/SocialGouv/docker/compare/v0.11.1...v0.11.2) (2019-11-07)


### Bug Fixes

* **kubectl:** update bash ([cea4553](https://github.com/SocialGouv/docker/commit/cea4553391ca69f3e80a4b671804af7326776d1a))

## [0.11.1](https://github.com/SocialGouv/docker/compare/v0.11.0...v0.11.1) (2019-10-30)


### Bug Fixes

* **helm:** add missing helm dependencies ([a67ae2b](https://github.com/SocialGouv/docker/commit/a67ae2bcedab7e466eb73ff6debe43c50d6ceb4e))

# [0.11.0](https://github.com/SocialGouv/docker/compare/v0.10.0...v0.11.0) (2019-10-30)


### Features

* **helm:** allow sudo ([106f7d4](https://github.com/SocialGouv/docker/commit/106f7d4be86bdb63c4925d23e6f5c548d2867e5f))

# [0.10.0](https://github.com/SocialGouv/docker/compare/v0.9.1...v0.10.0) (2019-10-30)


### Features

* **helm:** add su-exec ([fe736c5](https://github.com/SocialGouv/docker/commit/fe736c52347b9318569c71a8df8eeefcc1df10ff))

## [0.9.1](https://github.com/SocialGouv/docker/compare/v0.9.0...v0.9.1) (2019-10-28)


### Bug Fixes

* **gitlab:** add missing curl gitlab config in man gitlab file ([f58d073](https://github.com/SocialGouv/docker/commit/f58d073fae706f29ae0896ae36ce27650efbf534))

# [0.9.0](https://github.com/SocialGouv/docker/compare/v0.8.1...v0.9.0) (2019-10-28)


### Features

* **curl:** update curl image ([86caf1a](https://github.com/SocialGouv/docker/commit/86caf1aa9824a4671b18fd855ca17b9689ad7f3d))

## [0.8.1](https://github.com/SocialGouv/docker/compare/v0.8.0...v0.8.1) (2019-10-23)


### Reverts

* chore(deps): update alpine/helm docker tag to v2.15.0 ([#17](https://github.com/SocialGouv/docker/issues/17)) ([8459d2d](https://github.com/SocialGouv/docker/commit/8459d2d76b4975c864b483e0ec8044adf603f681))
* ci(gitlab): run jobs based on modified files ([a9e51c7](https://github.com/SocialGouv/docker/commit/a9e51c74e94a8e1a4832fd7bda4f38eb04cf3274))

# [0.8.0](https://github.com/SocialGouv/docker/compare/v0.7.2...v0.8.0) (2019-10-23)


### Features

* **helm:** update to kubctl 1.16.2 ([5c88253](https://github.com/SocialGouv/docker/commit/5c88253f7af6fc595b6a9f792f38bdb92df70abc))

## [0.7.2](https://github.com/SocialGouv/docker/compare/v0.7.1...v0.7.2) (2019-09-25)


### Bug Fixes

* **k8s-ns-killer:** change git branch exist check ([#15](https://github.com/SocialGouv/docker/issues/15)) ([e5da3d8](https://github.com/SocialGouv/docker/commit/e5da3d8))

## [0.7.1](https://github.com/SocialGouv/docker/compare/v0.7.0...v0.7.1) (2019-09-18)


### Bug Fixes

* **k8s-ns-killer:** test branch on remotes/origin ([eb3520d](https://github.com/SocialGouv/docker/commit/eb3520d))

# [0.7.0](https://github.com/SocialGouv/docker/compare/v0.6.0...v0.7.0) (2019-09-17)


### Features

* **kubectl:** add to depoly process ([db4131c](https://github.com/SocialGouv/docker/commit/db4131c))

# [0.6.0](https://github.com/SocialGouv/docker/compare/v0.5.2...v0.6.0) (2019-09-17)


### Features

* **kubectl:** update kubectl version to 1.15.3 ([5e8c071](https://github.com/SocialGouv/docker/commit/5e8c071))

## [0.5.2](https://github.com/SocialGouv/docker/compare/v0.5.1...v0.5.2) (2019-09-13)


### Bug Fixes

* **k8s-ns-killer:** check branch exists before the kill ([ef0b0ae](https://github.com/SocialGouv/docker/commit/ef0b0ae))

## [0.5.1](https://github.com/SocialGouv/docker/compare/v0.5.0...v0.5.1) (2019-09-13)


### Bug Fixes

* **k8s-ns-killer:** correctly check if the branch exists before k… ([#10](https://github.com/SocialGouv/docker/issues/10)) ([2b67bb6](https://github.com/SocialGouv/docker/commit/2b67bb6))

# [0.5.0](https://github.com/SocialGouv/docker/compare/v0.4.0...v0.5.0) (2019-09-12)


### Features

* **k8s-ns-killer:** add k8s-ns-killer image ([#8](https://github.com/SocialGouv/docker/issues/8)) ([2dd3cbd](https://github.com/SocialGouv/docker/commit/2dd3cbd))
* **k8s-ns-killer:** pass namespaces as script args ([9118b29](https://github.com/SocialGouv/docker/commit/9118b29))

# [0.4.0](https://github.com/SocialGouv/docker/compare/v0.3.0...v0.4.0) (2019-09-12)


### Features

* **helm:** update kubectl version in the image ([96480a1](https://github.com/SocialGouv/docker/commit/96480a1))

# [0.3.0](https://github.com/SocialGouv/docker/compare/v0.2.3...v0.3.0) (2019-09-06)


### Bug Fixes

* **publish:** allow publish to github registry to fail ([99bd3d7](https://github.com/SocialGouv/docker/commit/99bd3d7))


### Features

* **helm:** add to release process ([#7](https://github.com/SocialGouv/docker/issues/7)) ([5a4ee6f](https://github.com/SocialGouv/docker/commit/5a4ee6f))

## [0.2.3](https://github.com/SocialGouv/docker/compare/v0.2.2...v0.2.3) (2019-09-05)


### Bug Fixes

* **publish:** explicit tag from local image ([9ea5ea3](https://github.com/SocialGouv/docker/commit/9ea5ea3))

## [0.2.2](https://github.com/SocialGouv/docker/compare/v0.2.1...v0.2.2) (2019-09-05)


### Bug Fixes

* **publish:** explicit image name ([a736d53](https://github.com/SocialGouv/docker/commit/a736d53))

## [0.2.1](https://github.com/SocialGouv/docker/compare/v0.2.0...v0.2.1) (2019-09-05)


### Bug Fixes

* **publish:** explicit github registry ([d815f28](https://github.com/SocialGouv/docker/commit/d815f28))

# [0.2.0](https://github.com/SocialGouv/docker/compare/v0.1.0...v0.2.0) (2019-09-05)


### Features

* add github registry publish ([0371032](https://github.com/SocialGouv/docker/commit/0371032))
