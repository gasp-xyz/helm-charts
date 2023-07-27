# Changelog

## [1.2.0](https://github.com/mangata-finance/helm-charts/compare/node-v1.1.1...node-v1.2.0) (2023-07-27)


### Features

* Allow to use Kubernetes Volume Clone and Snapshots to provision new nodes MGX-533 ([94de3d9](https://github.com/mangata-finance/helm-charts/commit/94de3d9153aa1f505f827498c73aa305ad9b87bc))

## [1.1.1](https://github.com/mangata-finance/helm-charts/compare/node-v1.1.0...node-v1.1.1) (2023-07-24)


### Bug Fixes

* Fix author key injection MGX-533 ([a55e504](https://github.com/mangata-finance/helm-charts/commit/a55e5042a1e365fb14d86a7edb8a889de626b3e9))

## [1.1.0](https://github.com/mangata-finance/helm-charts/compare/node-v1.0.0...node-v1.1.0) (2023-07-24)


### Features

* Add tolerations and affinity configs MGX-533 ([366139c](https://github.com/mangata-finance/helm-charts/commit/366139cf00f761c2a8c1483bd85edc7a142d3b83))

## [1.0.0](https://github.com/mangata-finance/helm-charts/compare/node-v0.5.0...node-v1.0.0) (2023-07-17)


### ⚠ BREAKING CHANGES

* Major changes to keystore storage and monitoring configs MGX-445

### Features

* Major changes to keystore storage and monitoring configs MGX-445 ([e7774f2](https://github.com/mangata-finance/helm-charts/commit/e7774f24765b256b381ad8491b52b0e7dcc6f1e7))
* Update Helm charts to support new monitoring and update keystore mounting approach MGX-445 ([#21](https://github.com/mangata-finance/helm-charts/issues/21)) ([3ad658c](https://github.com/mangata-finance/helm-charts/commit/3ad658c456879ccc068dc2bc23f13fe98f597eb5))

## [0.5.0](https://github.com/mangata-finance/helm-charts/compare/node-v0.4.6...node-v0.5.0) (2023-05-03)


### Features

* add conditional startup probe enablement MGX-272 ([d1a975a](https://github.com/mangata-finance/helm-charts/commit/d1a975a8f3192d05287238a21a21bdd2e68582c5))

## [0.4.6](https://github.com/mangata-finance/helm-charts/compare/node-v0.4.5...node-v0.4.6) (2023-04-27)


### Features

* Kusama environment support updates MGX-272 ([#18](https://github.com/mangata-finance/helm-charts/issues/18)) ([91a7f2f](https://github.com/mangata-finance/helm-charts/commit/91a7f2f263780b04ebe61a260981b28c2eef4478))

## [0.4.5](https://github.com/mangata-finance/helm-charts/compare/node-v0.4.4...node-v0.4.5) (2023-04-27)


### Features

* Add role label for nodes MGX-444 ([#16](https://github.com/mangata-finance/helm-charts/issues/16)) ([942723b](https://github.com/mangata-finance/helm-charts/commit/942723bd7c16f724ee9dadad69f434fe4fd98079))

## [0.4.4](https://github.com/mangata-finance/helm-charts/compare/node-v0.4.3...node-v0.4.4) (2023-04-04)


### Features

* Add capability to not overwrite existing generated chainspec MGX-372 ([#14](https://github.com/mangata-finance/helm-charts/issues/14)) ([9a8b307](https://github.com/mangata-finance/helm-charts/commit/9a8b307b3b96242f347ad5eb27abc38f6684eff8))

## [0.4.3](https://github.com/mangata-finance/helm-charts/compare/node-v0.4.2...node-v0.4.3) (2023-04-03)


### Bug Fixes

* Fix chart configs to be compatible with fungible envs MGX-372 ([#12](https://github.com/mangata-finance/helm-charts/issues/12)) ([8fd85e4](https://github.com/mangata-finance/helm-charts/commit/8fd85e4554a2e963f79a4004fa024cef1de4017a))

## [0.4.2](https://github.com/mangata-finance/helm-charts/compare/node-v0.4.1...node-v0.4.2) (2023-03-27)


### Features

* Add chain data download init containers MGX-425 ([#10](https://github.com/mangata-finance/helm-charts/issues/10)) ([c9c84e6](https://github.com/mangata-finance/helm-charts/commit/c9c84e679814b07572883004ec3e011b095032a1))

## [0.4.1](https://github.com/mangata-finance/helm-charts/compare/node-v0.4.0...node-v0.4.1) (2023-02-24)


### Bug Fixes

* PodMonitoring selector config fix MGX-183 ([4fcf988](https://github.com/mangata-finance/helm-charts/commit/4fcf9889c24699733001507967f34d719a95d96d))

## [0.4.0](https://github.com/mangata-finance/helm-charts/compare/node-v0.3.1...node-v0.4.0) (2023-02-21)


### Features

* add podmonitoring resource support for metrics collection in GKE ([bc067ef](https://github.com/mangata-finance/helm-charts/commit/bc067ef633aac99207160d565230db0baa1c0247))

## [0.3.1](https://github.com/mangata-finance/helm-charts/compare/node-v0.3.0...node-v0.3.1) (2023-02-17)


### Features

* **MGX-241:** Add Helm chart reliability improvements  ([#3](https://github.com/mangata-finance/helm-charts/issues/3)) ([6985af1](https://github.com/mangata-finance/helm-charts/commit/6985af1d87650eda5b264be4387f0f244cc60af2))

## [0.3.0](https://github.com/mangata-finance/helm-charts/compare/node-v0.2.0...node-v0.3.0) (2023-02-10)


### Features

* update default relaychain image version to 37 in node chart ([a76e203](https://github.com/mangata-finance/helm-charts/commit/a76e203981127551a52dfb4237e7d2c83796b3ac))

## [0.2.0](https://github.com/mangata-finance/helm-charts/compare/node-v0.1.0...node-v0.2.0) (2023-02-03)


### Features

* **mgx-219:** automate certificates provisioning ([0af7eed](https://github.com/mangata-finance/helm-charts/commit/0af7eed288df35f23b1622488faac82319d53138))
* **MGX-241:** Add node Helm Chart adjusted for Rococo environment ([#2](https://github.com/mangata-finance/helm-charts/issues/2)) ([165e7c7](https://github.com/mangata-finance/helm-charts/commit/165e7c73f0578f5758dc0af41888bfc3be1265cf))
