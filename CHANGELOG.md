# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.1.1](https://github.com/boringcodes/prod-builder/compare/v0.1.0...v0.1.1) (2021-06-14)


### Bug Fixes

* **node:** remove ENV=production out from Dockerfile to fix yarn install does not install dev deps ([30aada1](https://github.com/boringcodes/prod-builder/commit/30aada13031e1352c0fb322b2f7044cd34f410c6))

## 0.1.0 (2021-06-14)


### Features

* implement docker alpine  node 10, 12, 14, 15 & 16 builders ([01ea1f4](https://github.com/boringcodes/prod-builder/commit/01ea1f47ff25de70b3234ac93d38fbfb312753f8))


### Bug Fixes

* **node:** missused RUN instead of CMD ([5a21c59](https://github.com/boringcodes/prod-builder/commit/5a21c5971da2c14439a8709285cbbeb5ad7641e2))
