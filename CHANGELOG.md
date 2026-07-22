## [2.0.0](https://github.com/restinthemiddle/helm/compare/v1.1.10...v2.0.0) (2026-07-22)

### ⚠ BREAKING CHANGES

* the chart now requires Kubernetes >= 1.23 (autoscaling/v2, networking.k8s.io/v1); helm template pipelines no longer emit explicit metadata.namespace on Deployment and ConfigMap.

### Features

* modernize chart and drop pre-1.23 Kubernetes support ([3a23a7e](https://github.com/restinthemiddle/helm/commit/3a23a7e9f1ff79d4a763b87ebf3367fefaa0dbc0))

## [1.1.10](https://github.com/restinthemiddle/helm/compare/v1.1.9...v1.1.10) (2026-07-16)

### Dependencies

* **deps:** update actions/checkout action to v7 ([e2e3191](https://github.com/restinthemiddle/helm/commit/e2e3191bac73f6df4b62dcc4a28f0dd46950ca4f))

## [1.1.9](https://github.com/restinthemiddle/helm/compare/v1.1.8...v1.1.9) (2026-07-12)

### Dependencies

* **deps:** update docker.io/jdschulze/restinthemiddle docker tag to v2.3.10 ([b6acc01](https://github.com/restinthemiddle/helm/commit/b6acc01bc5bb81a195c3002c4fb10036865403fe))

## [1.1.8](https://github.com/restinthemiddle/helm/compare/v1.1.7...v1.1.8) (2026-06-12)

### Dependencies

* **deps:** update docker.io/jdschulze/restinthemiddle docker tag to v2.3.9 ([d6831bf](https://github.com/restinthemiddle/helm/commit/d6831bf81ae28e2f11cb6621f784fa4b7ff46536))

## [1.1.7](https://github.com/restinthemiddle/helm/compare/v1.1.6...v1.1.7) (2026-06-07)

### Dependencies

* **deps:** update docker.io/jdschulze/restinthemiddle docker tag to v2.3.8 ([f57acd1](https://github.com/restinthemiddle/helm/commit/f57acd13c523bca78cecc5f16a112a6443eddf1c))

## [1.1.6](https://github.com/restinthemiddle/helm/compare/v1.1.5...v1.1.6) (2026-04-28)

### Dependencies

* **deps:** update docker.io/jdschulze/restinthemiddle docker tag to v2.3.7 ([01b041a](https://github.com/restinthemiddle/helm/commit/01b041a3203ab1b95be6155e1e1bb885e03ebb79))

## [1.1.5](https://github.com/restinthemiddle/helm/compare/v1.1.4...v1.1.5) (2026-04-20)

### Bug Fixes

* **ci:** add workflow_dispatch trigger to release workflow ([9094f22](https://github.com/restinthemiddle/helm/commit/9094f22ea1bff11712e3683d04d726ca0781a0a3))

## [1.1.4](https://github.com/restinthemiddle/helm/compare/v1.1.3...v1.1.4) (2026-04-20)

### Bug Fixes

* **ci:** decouple semantic-release and chart-releaser tag formats ([a4a85e6](https://github.com/restinthemiddle/helm/commit/a4a85e611a9612f060fc0d635239094cf1416cc3))

## [1.1.3](https://github.com/restinthemiddle/helm/compare/restinthemiddle-1.1.2...restinthemiddle-1.1.3) (2026-04-20)

## [1.1.2](https://github.com/restinthemiddle/helm/compare/restinthemiddle-1.1.1...restinthemiddle-1.1.2) (2026-04-20)

## [1.1.1](https://github.com/restinthemiddle/helm/compare/restinthemiddle-1.1.0...restinthemiddle-1.1.1) (2026-01-19)

<a name="unreleased"></a>
## [Unreleased]


<a name="restinthemiddle-0.10.0"></a>
## [restinthemiddle-0.10.0] - 2023-08-04
### Feat
- add appProtocol field to Service


<a name="restinthemiddle-0.9.1"></a>
## [restinthemiddle-0.9.1] - 2023-08-04
### Fix
- unignore README.md


<a name="restinthemiddle-0.9.0"></a>
## [restinthemiddle-0.9.0] - 2023-08-03
### Feat
- start a new pod if ConfigMap changes


<a name="restinthemiddle-0.8.0"></a>
## [restinthemiddle-0.8.0] - 2023-08-03
### Feat
- upgrade version and increase security


<a name="restinthemiddle-0.7.2"></a>
## [restinthemiddle-0.7.2] - 2023-08-03
### Fix
- **cm:** rename ConfigMap again and rename reference in Deployment accordingly


<a name="restinthemiddle-0.7.1"></a>
## [restinthemiddle-0.7.1] - 2023-08-03
### Fix
- **cm:** use fullname template for ConfigMap name


<a name="restinthemiddle-0.7.0"></a>
## [restinthemiddle-0.7.0] - 2023-05-04
### Feat
- add podLabels


<a name="restinthemiddle-0.6.0"></a>
## [restinthemiddle-0.6.0] - 2023-01-29
### Feat
- publish chart version 0.6.0


<a name="restinthemiddle-0.5.0"></a>
## [restinthemiddle-0.5.0] - 2023-01-18
### Feat
- bump chart version


<a name="restinthemiddle-0.4.0"></a>
## [restinthemiddle-0.4.0] - 2023-01-18

<a name="0.3.1"></a>
## [0.3.1] - 2023-01-18
### Fix
- wrong restinthemiddle version


<a name="0.3.0"></a>
## [0.3.0] - 2023-01-18
### Feat
- use restinthemiddle v2


<a name="0.2.0"></a>
## [0.2.0] - 2021-09-26

<a name="0.1.3"></a>
## [0.1.3] - 2021-08-25
### Fix
- unify namespace source


<a name="0.1.2"></a>
## [0.1.2] - 2021-08-25
### Fix
- improve port handling


<a name="0.1.1"></a>
## [0.1.1] - 2021-08-23
### Fix
- unify namespace source (Release)


<a name="0.1.0"></a>
## 0.1.0 - 2021-07-28

[Unreleased]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.10.0...HEAD
[restinthemiddle-0.10.0]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.9.1...restinthemiddle-0.10.0
[restinthemiddle-0.9.1]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.9.0...restinthemiddle-0.9.1
[restinthemiddle-0.9.0]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.8.0...restinthemiddle-0.9.0
[restinthemiddle-0.8.0]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.7.2...restinthemiddle-0.8.0
[restinthemiddle-0.7.2]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.7.1...restinthemiddle-0.7.2
[restinthemiddle-0.7.1]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.7.0...restinthemiddle-0.7.1
[restinthemiddle-0.7.0]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.6.0...restinthemiddle-0.7.0
[restinthemiddle-0.6.0]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.5.0...restinthemiddle-0.6.0
[restinthemiddle-0.5.0]: https://github.com/restinthemiddle/helm/compare/restinthemiddle-0.4.0...restinthemiddle-0.5.0
[restinthemiddle-0.4.0]: https://github.com/restinthemiddle/helm/compare/0.3.1...restinthemiddle-0.4.0
[0.3.1]: https://github.com/restinthemiddle/helm/compare/0.3.0...0.3.1
[0.3.0]: https://github.com/restinthemiddle/helm/compare/0.2.0...0.3.0
[0.2.0]: https://github.com/restinthemiddle/helm/compare/0.1.3...0.2.0
[0.1.3]: https://github.com/restinthemiddle/helm/compare/0.1.2...0.1.3
[0.1.2]: https://github.com/restinthemiddle/helm/compare/0.1.1...0.1.2
[0.1.1]: https://github.com/restinthemiddle/helm/compare/0.1.0...0.1.1
