# Changelog

## [0.11.1](https://github.com/saltstack-formulas/packages-formula/compare/v0.11.0...v0.11.1) (2020-10-23)


### Bug Fixes

* **states:** deploy packages only if required ([c9fe187](https://github.com/saltstack-formulas/packages-formula/commit/c9fe187e1677cc2645d7ed479ab2d32749d38d30))


### Continuous Integration

* **kitchen:** use `saltimages` Docker Hub where available [skip ci] ([3a80123](https://github.com/saltstack-formulas/packages-formula/commit/3a80123db0be1d8f291c606f61634fa2c8597c5e))
* **pre-commit:** add to formula [skip ci] ([62e73fe](https://github.com/saltstack-formulas/packages-formula/commit/62e73fe14cab553603aab6d986199c05457ddcff))
* **pre-commit:** enable/disable `rstcheck` as relevant [skip ci] ([22fa2e8](https://github.com/saltstack-formulas/packages-formula/commit/22fa2e873719d296fab0a9af83c56732b158f275))
* **pre-commit:** finalise `rstcheck` configuration [skip ci] ([d64b8d8](https://github.com/saltstack-formulas/packages-formula/commit/d64b8d8b73fe3ed531c58b6dfdbf5f69201e5cf2))


### Tests

* **npm:** changed package to an existing one ([8a51ae5](https://github.com/saltstack-formulas/packages-formula/commit/8a51ae5f559d5918f37bc0b3fc19da7cc3c88045))
* **snaps:** disable classic snaps testing in debian ([bb60deb](https://github.com/saltstack-formulas/packages-formula/commit/bb60deb20bd7b5cb819f88a1257bba8343729731))
* **ubuntu:** update for `golang` fix [skip ci] ([0226c88](https://github.com/saltstack-formulas/packages-formula/commit/0226c880b8f5b452e6be710b5d1afd3c2d62a6f4))

# [0.11.0](https://github.com/saltstack-formulas/packages-formula/compare/v0.10.2...v0.11.0) (2020-06-01)


### Continuous Integration

* **kitchen+travis:** use latest pre-salted images ([bfcdd9c](https://github.com/saltstack-formulas/packages-formula/commit/bfcdd9cd591837723f8773005e0574815489b61a))


### Features

* **fedora:** update for Python 3 ([0175a48](https://github.com/saltstack-formulas/packages-formula/commit/0175a4811285c4a11f2fa3ac6e4507bc913c0a1d))

## [0.10.2](https://github.com/saltstack-formulas/packages-formula/compare/v0.10.1...v0.10.2) (2020-06-01)


### Bug Fixes

* **pillar:** update `node.pkg` => `node.package` ([a6d3c98](https://github.com/saltstack-formulas/packages-formula/commit/a6d3c98ae7cc3949feb060c95817250513536e8f))


### Documentation

* **readme:** fix various issues inc. not rendering properly [skip ci] ([5701df0](https://github.com/saltstack-formulas/packages-formula/commit/5701df06a9f60d1c3aa717d9a295655c14075223))

## [0.10.1](https://github.com/saltstack-formulas/packages-formula/compare/v0.10.0...v0.10.1) (2020-06-01)


### Bug Fixes

* **python:** os default to python3 ([662a8d0](https://github.com/saltstack-formulas/packages-formula/commit/662a8d092da7c0c6fe92ad6aed974e1c87c1f58d))


### Continuous Integration

* **gemfile.lock:** add to repo with updated `Gemfile` [skip ci] ([0628bf0](https://github.com/saltstack-formulas/packages-formula/commit/0628bf029f0d80f8caab45c191ba28ef2e0af18a))
* **kitchen+travis:** remove `master-py2-arch-base-latest` [skip ci] ([fb311a4](https://github.com/saltstack-formulas/packages-formula/commit/fb311a42074acf58c3e9e39d6281d7faf766dede))
* **travis:** add notifications => zulip [skip ci] ([57a1b14](https://github.com/saltstack-formulas/packages-formula/commit/57a1b1449f7119206f4a7f634b61cb7a6724c494))
* **workflows/commitlint:** add to repo [skip ci] ([9220ceb](https://github.com/saltstack-formulas/packages-formula/commit/9220ceb46b98628a8292e0f5f4cbf24164acc1d5))

# [0.10.0](https://github.com/saltstack-formulas/packages-formula/compare/v0.9.0...v0.10.0) (2020-03-30)


### Bug Fixes

* **chocolatey:** ensure states only run on Windows systems ([c1d680a](https://github.com/saltstack-formulas/packages-formula/commit/c1d680a9dd0863497ca004dcf41378fa0e5707f9))
* **chocolatey:** verify chocolatey dicts are not empty ([385b223](https://github.com/saltstack-formulas/packages-formula/commit/385b2238f4c8bc9389728cc6f90e320bc74b077c))


### Documentation

* **changelog:** merge old changelog into the new one ([070172d](https://github.com/saltstack-formulas/packages-formula/commit/070172db89f2762b11c73c8d149619ce1f197167))


### Features

* **chocolatey:** add chocolatey management support ([c0c1195](https://github.com/saltstack-formulas/packages-formula/commit/c0c119524228e30ed19f6fe8714d47b06915ff43))

# [0.9.0](https://github.com/saltstack-formulas/packages-formula/compare/v0.8.0...v0.9.0) (2020-03-28)


### Bug Fixes

* **lint:** remove whitespace ([c03bb25](https://github.com/saltstack-formulas/packages-formula/commit/c03bb255317716543c092431adf19cac2c0e7463))


### Continuous Integration

* **kitchen:** avoid using bootstrap for `master` instances [skip ci] ([d93e3d2](https://github.com/saltstack-formulas/packages-formula/commit/d93e3d2584b2a5a0e65458b65a104f188568251b))
* **kitchen:** reinstall `udev` since removed from pre-salted images ([a81f2dd](https://github.com/saltstack-formulas/packages-formula/commit/a81f2dd4b337ebe2a898ed8ed91e585e5f19b254))


### Features

* **centos:** epel only needed for py-pip ([a0dd96d](https://github.com/saltstack-formulas/packages-formula/commit/a0dd96d6635306a675f89b2b607db4abc4096251))


### Tests

* **pillar:** disable `dxpy` on Ubuntu (works locally) ([155bdeb](https://github.com/saltstack-formulas/packages-formula/commit/155bdeb7b92d2d06a8d2147e21ad46dff9433aee)), closes [verify#L4793-L4859](https://github.com/verify/issues/L4793-L4859)
* **pillar:** update `node` version for Debian ([a9f120f](https://github.com/saltstack-formulas/packages-formula/commit/a9f120fa6aea35e96ff3d1ef2338bfaeb742afdf))

# [0.8.0](https://github.com/saltstack-formulas/packages-formula/compare/v0.7.0...v0.8.0) (2020-01-20)


### Bug Fixes

* **archlinux:** fix test setup ([281846e](https://github.com/saltstack-formulas/packages-formula/commit/281846e79165872a17d8bd143f2f6b05e0b4da9b))
* **centos:** fix tests ([a4d4d1d](https://github.com/saltstack-formulas/packages-formula/commit/a4d4d1dc734add260ca9b408a67754663c4636bb))
* **gem:** fix `invalid option: --no-rdoc` & `invalid option: --no-ri` ([16c4213](https://github.com/saltstack-formulas/packages-formula/commit/16c4213ab99204e01a040155782a9c158f64e2a9))
* **golang:** ensure state runs ([0f992d9](https://github.com/saltstack-formulas/packages-formula/commit/0f992d9c17b36b37078ac3866b9d2ec4240ebf0b))
* **golang:** ensure using on `ubuntu` ([bd909bd](https://github.com/saltstack-formulas/packages-formula/commit/bd909bd1b63d5678431789980f4650dcb8246012))
* **golang_spec.rb:** fix `rubocop` errors ([08340c8](https://github.com/saltstack-formulas/packages-formula/commit/08340c857a54d67b8310a69558c45c37fd5600fb))
* **node:** ensure using on `debian` ([eca4228](https://github.com/saltstack-formulas/packages-formula/commit/eca4228906d119803a8e0bcf8c4eac33c1babeb3))
* **pips.sls:** use `tplroot` instead of `slspath` ([a4e9311](https://github.com/saltstack-formulas/packages-formula/commit/a4e9311a357808fd608c0e0de638ec3d4889235b)), closes [/travis-ci.org/myii/packages-formula/jobs/636188022#L7867](https://github.com//travis-ci.org/myii/packages-formula/jobs/636188022/issues/L7867)
* **rubocop:** add fixes using `rubocop -a --safe` ([1f72c40](https://github.com/saltstack-formulas/packages-formula/commit/1f72c405de9dd01de1070e37d7d8cbdea41e66ad))
* **rubocop:** fix remaining errors manually ([591d85a](https://github.com/saltstack-formulas/packages-formula/commit/591d85ab5725e6eb45122adebff6c66d894d86ec))
* **salt-lint:** fix all errors ([83ed92b](https://github.com/saltstack-formulas/packages-formula/commit/83ed92bf64ab63ce2a3e0af3f93bb7bb16f87be7))
* **yamllint:** fix all errors ([4176716](https://github.com/saltstack-formulas/packages-formula/commit/4176716f7e45bf9023b29c79e2de4572b1a4e5ec))


### Code Refactoring

* **map:** use `config.get` instead of `pillar.get` ([ca9bbd1](https://github.com/saltstack-formulas/packages-formula/commit/ca9bbd15a12b2ff5df69fc2c17cb8ace12f095fe))
* **pillar.amazonlinux:** shorten suite name to `amazon` ([593a6e5](https://github.com/saltstack-formulas/packages-formula/commit/593a6e5e65557aaca186065314543aa17d13d8f1))
* **test_pillars:** rename to make accessible to `yamllint` ([033ff44](https://github.com/saltstack-formulas/packages-formula/commit/033ff4453f7c2a3cc23785425b10705ecb6fbaa9))


### Continuous Integration

* **inspec:** fix Debian tests ([98c6d2c](https://github.com/saltstack-formulas/packages-formula/commit/98c6d2c9bad3e0c4caad51fd27bde3192cf6df0f))
* **inspec:** removing useless inspec tests ([3615785](https://github.com/saltstack-formulas/packages-formula/commit/3615785e52c671d32fe0b71fd784f25e3beff5d1))
* **kitchen:** fix tests with a minimal coverage ([288f893](https://github.com/saltstack-formulas/packages-formula/commit/288f8936528c9dc33af519314aa36ea69747588b))
* **kitchen+inspec:** add Amazonlinux test suite ([edb0d73](https://github.com/saltstack-formulas/packages-formula/commit/edb0d73ffe0c2a02d3b3d69149ce1edd6b65634e))
* **kitchen+inspec:** add Centos test suite ([d320ccd](https://github.com/saltstack-formulas/packages-formula/commit/d320ccd36b1d1f0a0d70a16a81df7cf0072a1d8c))
* **kitchen+inspec:** add fedora30 and fedora29 tests suites ([e41117c](https://github.com/saltstack-formulas/packages-formula/commit/e41117c34b6f314b7f10ee5a661985c6cc004018))
* **kitchen+inspec:** add initial support for opensuse ([58b1209](https://github.com/saltstack-formulas/packages-formula/commit/58b1209d9a67d59c3b6a2df4b975c2b4690535af))
* **kitchen+inspec:** add Ubuntu test suite ([39ba77d](https://github.com/saltstack-formulas/packages-formula/commit/39ba77d04443abd4d543337ac9cf1e8ae05d5207))
* **pillars:** use one retry to prevent excessive slow-down in Travis ([48ae3c9](https://github.com/saltstack-formulas/packages-formula/commit/48ae3c98fdcc9e6117efb006334e2ac93afc3d40))


### Features

* **semantic-release:** update for this formula ([1755f76](https://github.com/saltstack-formulas/packages-formula/commit/1755f76fde53a8af1641deda393bd8fad3b40230))
* implementing semantic release ([17b4331](https://github.com/saltstack-formulas/packages-formula/commit/17b433126b6e5f7eb5cbfb93558657262e41699b))
* **golang:** add go package management ([284b240](https://github.com/saltstack-formulas/packages-formula/commit/284b240c331a109937dbfceebcb83b44f98e18bf))
* **internet:** add retries for internet dependent states ([7660dbd](https://github.com/saltstack-formulas/packages-formula/commit/7660dbd76f092fc90635804afe5af32cdad66755))


### Tests

* **arch:** test initial configuration ([702e8c3](https://github.com/saltstack-formulas/packages-formula/commit/702e8c32bfaa5f7fc3695fd6421f9c47c0edc057))
* **fedora:** merge fedora test suites and pillars ([89911dc](https://github.com/saltstack-formulas/packages-formula/commit/89911dc9c8aec1ecd83755f5bf6d1deaf216d349))
* **golang:** basic integrtaion test & tweaks ([6c3de22](https://github.com/saltstack-formulas/packages-formula/commit/6c3de2231d136c9d9eb57e232523d0a360ff54f0))
* **pillar:** use single ubuntu pillar ([c69cb5a](https://github.com/saltstack-formulas/packages-formula/commit/c69cb5a792186a8a1600987087389229ddf7a67a))
* **pillar:** use specific pillar for `debian` ([adf1523](https://github.com/saltstack-formulas/packages-formula/commit/adf1523e08bfeff8d635052a8942b48326e507cb))
* fix existing tests ([8e75c9d](https://github.com/saltstack-formulas/packages-formula/commit/8e75c9d5c0c4af5fe4e56ecfcdfcc7ea7486d4dc))
