# Changelog

All notable changes to this project will be documented in this file.

## [9.15.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.14.0...v9.15.0) (2025-06-19)


### Features

* DSQL Support ([#508](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/508)) ([dad2482](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/dad2482222e16cf62ba528c5bb15185b6f584d9d))

## [9.14.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.13.0...v9.14.0) (2025-06-04)


### Features

* Add `create_before_destroy` to Aurora DB instance resource ([#506](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/506)) ([6468f81](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/6468f81cf317a95a4810f1d796a7ca4abeb276f2))

## [9.13.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.12.0...v9.13.0) (2025-03-04)


### Features

* Support Aurora Limitless ([#488](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/488)) ([cf96537](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/cf965379f7370be440566156bcfa0e2883277629))

## [9.12.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.11.0...v9.12.0) (2025-02-19)


### Features

* Support RDS Cluster monitoring interval and role arn  ([#485](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/485)) ([b172e08](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/b172e0815292229ede381e2f8132b83ba7ad418c))

## [9.11.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.10.0...v9.11.0) (2024-12-19)


### Features

* Support `serverlessv2_scaling_configuration.seconds_until_auto_pause` ([#477](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/477)) ([08dced9](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/08dced981559788559a3e69f288d51047aa64220))

## [9.10.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.9.1...v9.10.0) (2024-10-15)


### Features

* Add `cloudwatch_log_group_tags` parameter for log group tags ([#472](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/472)) ([0962ab8](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/0962ab868a7967e03d16fca5f7f25cdf580bd13d))


### Bug Fixes

* Update CI workflow versions to latest ([#471](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/471)) ([a11c970](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/a11c97093dae1469722d503428953cfec0e16aa5))

## [9.9.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.9.0...v9.9.1) (2024-08-24)


### Bug Fixes

* AWS provider bump for bugfix on `enable_http_endpoint` ([#465](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/465)) ([f64d755](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/f64d755c46e6ca45a5f3d21d6578a14834e8b5e9))

## [9.9.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.8.0...v9.9.0) (2024-08-14)


### Features

* Add "self" attribute to the security group rule ([#463](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/463)) ([6e4b82c](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/6e4b82c706c3587505cd50a992fa28b807eefcec))

## [9.8.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.7.0...v9.8.0) (2024-08-05)


### Features

* Multi-AZ Cluster performance insights ([#462](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/462)) ([546c74a](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/546c74a87c1a1c09e486153651ccb4a6719cb39e))

## [9.7.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.6.0...v9.7.0) (2024-07-27)


### Features

* Support for `scaling_configuration.seconds_before_timeout` in Serverless V1 ([#461](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/461)) ([d798147](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/d7981474a4ec2a0a53900c41d25b31329fab2afd))

## [9.6.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.5.0...v9.6.0) (2024-07-20)


### Features

* Support `engine_lifecycle_support` ([#459](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/459)) ([466f090](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/466f090b277e92b6d26c00af97ab55e75439f736))

## [9.5.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.4.0...v9.5.0) (2024-07-12)


### Features

* Multi-az rds cluster ca cert identifier ([#458](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/458)) ([d320348](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/d320348984db35c28ca8d272407e5c45ead983ae))

## [9.4.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.3.1...v9.4.0) (2024-05-27)


### Features

* Cloudwatch log group `skip_destroy` and `log_group_class` ([#449](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/449)) ([683c069](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/683c06916598028af568e2fc05738a0224c3b393))

## [9.3.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.3.0...v9.3.1) (2024-03-26)


### Bug Fixes

* Do not create dynamic DNS suffix for service principals ([#442](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/442)) ([b79c17a](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/b79c17a0eaa1513f0949316b2f38b2becbb6add6))

## [9.3.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.2.1...v9.3.0) (2024-03-22)


### Features

* Support for `enable_local_write_forwarding` ([#441](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/441)) ([8c6039e](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/8c6039e9e0cf4d357b7f2af72c6551e5239e9f76))

## [9.2.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.2.0...v9.2.1) (2024-03-06)


### Bug Fixes

* Update CI workflow versions to remove deprecated runtime warnings ([#435](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/435)) ([98dd426](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/98dd426b9c0a7814921fc4239cf61a5401b488f6))

## [9.2.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.1.0...v9.2.0) (2024-03-05)


### Features

* Secretsmanager secret rotation for master user password ([#433](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/433)) ([ae752de](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/ae752de086b9ab6f9a1178024d1e99dce9852d37))

## [9.1.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.0.2...v9.1.0) (2024-02-16)


### Features

* Add `domain` support ([#429](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/429)) ([29bb9d6](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/29bb9d68565cc1ecc73c142b14d61723a275ee30))

### [9.0.2](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.0.1...v9.0.2) (2024-02-15)


### Bug Fixes

* Ignore `tags_all` for `aws_appautoscaling_target` ([#431](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/431)) ([fa8caad](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/fa8caaddeb294e7898c081a63f2a144920a833e1))

### [9.0.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v9.0.0...v9.0.1) (2024-02-15)


### Bug Fixes

* Allow Serverless maintenance windows ([#427](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/427)) ([c7d2e77](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/c7d2e776cadc52d4ad59a8f8e1e5fbfe733f1f56))

## [9.0.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.5.0...v9.0.0) (2023-12-11)


### ⚠ BREAKING CHANGES

* Add `delete_automated_backups` and update MSV of AWS provider to `v5.26` to support (#415)

### Features

* Add `delete_automated_backups` and update MSV of AWS provider to `v5.26` to support ([#415](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/415)) ([c9e4933](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/c9e4933177c6d972dca6c45be0178dc2928e42b1))

## [8.5.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.4.0...v8.5.0) (2023-10-09)


### Features

* Add RDS cluster activity stream ([#407](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/407)) ([783c686](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/783c6864d4fe0d610a62d00d5ff8e5edb08a008a))

## [8.4.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.3.1...v8.4.0) (2023-10-09)


### Features

* Enable db_parameter_group_name per instance ([#410](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/410)) ([d34e83c](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/d34e83c6ecfbf7625ca4f50f9a3d703a8fd39e9a))

### [8.3.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.3.0...v8.3.1) (2023-06-07)


### Bug Fixes

* Tag Application AutoScaling target ([#389](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/389)) ([04ffe1c](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/04ffe1ce2675eb1b230fc52f7a67473ae08ac019))

## [8.3.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.2.0...v8.3.0) (2023-06-01)


### Features

* Enable support for v5.0 of the AWS provider ([#385](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/385)) ([959228c](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/959228c5fa33277139432fe3a858013b2b93c3ab))

## [8.2.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.1.1...v8.2.0) (2023-05-24)


### Features

* Upgrade aws provider version and update examples ([#382](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/382)) ([b792d84](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/b792d84b68086e1458fb9ef0ee07dc982510f4ed))

### [8.1.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.1.0...v8.1.1) (2023-05-12)


### Bug Fixes

* Tag security group with correct name ([#380](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/380)) ([71d23db](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/71d23db753184f416e06c0d0c6f4f73ec8d95184))

## [8.1.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.0.2...v8.1.0) (2023-05-12)


### Features

* Ability to set custom `security_group_name` ([#379](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/379)) ([67edcaa](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/67edcaafe8b08226929a0cc989b1fbc39fcff8d1))

### [8.0.2](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.0.1...v8.0.2) (2023-04-11)


### Bug Fixes

* Allow setting `master_username` when using `manage_master_user_password` ([#369](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/369)) ([f48f824](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/f48f824d76ff1970cff91d336349f956556c75b2))

### [8.0.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v8.0.0...v8.0.1) (2023-04-10)


### Bug Fixes

* Variable description for `master_username` requirements ([#367](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/367)) ([d0435c6](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/d0435c6eaee5e28375bf241362fd7dd4b40e1aca))

## [8.0.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.7.1...v8.0.0) (2023-04-10)


### ⚠ BREAKING CHANGES

* Terraform MSV increased to 1.0, consolidate security group rules under one generic resource, add support for managed master password (#335)

### Features

* Terraform MSV increased to 1.0, consolidate security group rules under one generic resource, add support for managed master password ([#335](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/335)) ([e054f77](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/e054f77c700128c206b0912c51712313981d6fae))

### [7.7.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.7.0...v7.7.1) (2023-04-04)


### Bug Fixes

* Postgres port conditional adjustment ([#362](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/362)) ([980ce16](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/980ce164cc66d5b7ef1dca02cc64f47bc3ab4e66))

## [7.7.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.6.2...v7.7.0) (2023-03-06)


### Features

* Add support for creating CloudWatch log groups ([#346](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/346)) ([40cef84](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/40cef841e42cffa9c379397a4294f7a5650c4993))

### [7.6.2](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.6.1...v7.6.2) (2023-02-07)


### Bug Fixes

* Add explicit default value for `engine_mode` used in conditiona logic internally ([#347](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/347)) ([7ffa33f](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/7ffa33f82603830713ba31aa2d18f421a0abf4d8))

### [7.6.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.6.0...v7.6.1) (2023-02-06)


### Bug Fixes

* Use `create_before_destroy` lifecycle on parameter groups to support major version upgrades ([#354](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/354)) ([97c417a](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/97c417aeddf9b5e51183f50a3fa1fe2a9be0a2c9))

## [7.6.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.5.1...v7.6.0) (2022-10-19)


### Features

* Do not create `snapshot_identifier` when `skip_final_snapshot = true` ([#332](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/332)) ([7ce592e](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/7ce592ea90caea4adc8a0d3e74e83a478b17b374))

### [7.5.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.5.0...v7.5.1) (2022-09-12)


### Bug Fixes

* Update miminum provider version required for current arguments supported ([#324](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/324)) ([5f61877](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/5f61877726774ce49d9bfdc77f9934e33eb3f06e))

## [7.5.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.4.2...v7.5.0) (2022-09-12)


### Features

* Add support for network_type argument ([#322](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/322)) ([e54fbd7](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/e54fbd775ebd2c26ce6e61012b5cf52b1def1640))

### [7.4.2](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.4.1...v7.4.2) (2022-09-10)


### Bug Fixes

* Correct DB instance parameter group used when users do not create one nor provide the name of existing, will use default ([#321](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/321)) ([3a5ba14](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/3a5ba1441905f6e100a129f37f421f45e0d2ec1f))

### [7.4.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.4.0...v7.4.1) (2022-09-08)


### Bug Fixes

* Correct DB clsuter parameter group used when users do not create one nor provide the name of existing, will use default ([#320](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/320)) ([c1e7002](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/c1e7002c1275d80ee8b0a3a11028735191e1d234))

## [7.4.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.3.0...v7.4.0) (2022-09-07)


### Features

* Fix serverless v2 engine and add missing resource arguments ([#317](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/317)) ([2d87320](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/2d87320cbc49dbb2201b7871ba010bbc5a8d6c2b))

## [7.3.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.2.2...v7.3.0) (2022-08-17)


### Features

* Support feature to create parameter group for aws-rds-aurora cluster and instances ([#307](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/307)) ([45d7bf7](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/45d7bf742e1ffe9cc49b0e9e3e5be6e89414640a))

### [7.2.2](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.2.1...v7.2.2) (2022-07-11)


### Bug Fixes

* InvalidParameterCombination: Cannot find version 5.7.12 for aurora-mysql ([#303](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/303)) ([bcbb386](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/bcbb386e0854bc1968c271bb3f49a5a106fbcec9))

### [7.2.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.2.0...v7.2.1) (2022-06-27)


### Bug Fixes

* SecurityGroup - create_before_destroy ([#301](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/301)) ([ceb91fb](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/ceb91fb0153aa2cd92d3bfa67c458998901530a0))

## [7.2.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.1.0...v7.2.0) (2022-06-20)


### Features

* Add MySql serverless v2 example ([#295](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/295)) ([0390b59](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/0390b59a279eb9a02126df29c43f5cc828d3870f))

## [7.1.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v7.0.0...v7.1.0) (2022-05-02)


### Features

* Add `security_group_use_name_prefix` variable to enable/disable name prefix usage ([#289](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/289)) ([75ffb30](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/75ffb30cd6032622ac28f4c5c16e47aba069e11f))

## [7.0.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v6.2.0...v7.0.0) (2022-05-02)


### ⚠ BREAKING CHANGES

* Added support for ServerlessV2 and updated AWS provider to v4.12+ (#288)

### Features

* Added support for ServerlessV2 and updated AWS provider to v4.12+ ([#288](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/288)) ([6ca7c70](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/6ca7c705f382c2d5aec0df5a0aa6f6c198871dec))

## [6.2.0](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v6.1.4...v6.2.0) (2022-03-12)


### Features

* Made it clear that we stand with Ukraine ([57c20b9](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/57c20b9f96c6fdf7664a5fc6b6c9a677f819b99d))

### [6.1.4](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v6.1.3...v6.1.4) (2022-01-10)


### Bug Fixes

* update CI/CD process to align auto-release workflow ([#259](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/259)) ([d00931e](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/d00931e97350a1e2f04b60328ba10dbbe823e44c))

## [6.1.3](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v6.1.2...v6.1.3) (2021-11-08)


### Bug Fixes

* Revert small useless change in main.tf ([#256](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/256)) ([40c146a](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/40c146abec001e10bbd7a379943579c338da3d67))

# Changelog

All notable changes to this project will be documented in this file

## [6.1.2](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v6.1.1...v6.1.2) (2021-11-08)


### Bug Fixes

* Small useless change in main.tf to test semantic-release ([#254](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/254)) ([95bb77f](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/95bb77f2797cdb1760fdd52203b5710273a6603b))
* Small useless change in main.tf to test semantic-release (last one, I promise) ([#255](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/255)) ([8b3525e](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/8b3525e7930c0ca43124432e416f6ec35ab7618e))

## [6.1.1](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v6.1.0...v6.1.1) (2021-11-08)


### Bug Fixes

* update CI/CD process to enable auto-release workflow ([#250](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/250)) ([b44aae5](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/commit/b44aae50ff2785a6a2a04691ba87d4589b4fa102))

<a name="v6.1.0"></a>
## [v6.1.0] - 2021-11-06

- feat: Add security group egress rule support, fix documentation links ([#249](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/249))


<a name="v6.0.0"></a>
## [v6.0.0] - 2021-10-25

- chore: Updated release Makefile
- BREAKING CHANGE: update module to allow for control over individual cluster instances and latest features ([#243](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/243))
- chore: update CI workflow to use composite actions, update pre-commit versions ([#242](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/242))


<a name="v5.3.0"></a>
## [v5.3.0] - 2021-10-13

- feat: Add support for restore_to_point_in_time ([#194](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/194))
- chore: Updated README to use version 5 of the module ([#235](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/235))
- chore: update CI/CD to use stable `terraform-docs` release artifact and discoverable Apache2.0 license ([#219](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/219))


<a name="v5.2.0"></a>
## [v5.2.0] - 2021-04-30

- fix: Don't use instance_type_replica for main replica ([#211](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/211))


<a name="v5.1.0"></a>
## [v5.1.0] - 2021-04-30

- chore: add output for cluster instance `db_resource_id` output list ([#218](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/218))


<a name="v5.0.0"></a>
## [v5.0.0] - 2021-04-26

- feat: Shorten outputs (removing this_) ([#216](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/216))


<a name="v4.3.0"></a>
## [v4.3.0] - 2021-04-24

- fix: mark sensitive outputs to support Terraform 0.15.x ([#215](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/215))


<a name="v4.2.0"></a>
## [v4.2.0] - 2021-04-21

- fix: set backup and maintenance windows to `null` when using serverless mode ([#213](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/213))


<a name="v4.1.0"></a>
## [v4.1.0] - 2021-04-13

- docs: Clarify description of skip_final_snapshot variable ([#209](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/209))
- chore: update documentation and pin `terraform_docs` version to avoid future changes ([#207](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/207))


<a name="v4.0.0"></a>
## [v4.0.0] - 2021-03-25

- feat: Simplify instrance_parameters (Terraform 0.13) ([#206](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/206))


<a name="v3.13.0"></a>
## [v3.13.0] - 2021-03-21

- feat: Additional tags for security group ([#205](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/205))


<a name="v3.12.0"></a>
## [v3.12.0] - 2021-03-19

- fix: when `engine_mode` is `serverless`, set `engine_version` to `null` ([#204](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/204))


<a name="v3.11.0"></a>
## [v3.11.0] - 2021-03-18

- fix: Bump AWS provider version ([#202](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/202))


<a name="v3.10.0"></a>
## [v3.10.0] - 2021-03-14

- chore: add all attributes and some outputs for enhanced monitoring IAM role ([#201](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/201))


<a name="v3.9.0"></a>
## [v3.9.0] - 2021-03-13

- chore: update examples to to be self-sufficient and using latest practices/versions ([#200](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/200))
- chore: update README documentation and reference to license ([#199](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/199))


<a name="v3.8.0"></a>
## [v3.8.0] - 2021-03-08

- feat: AWS Instance Scheduler Tagging Support ([#198](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/198))


<a name="v3.7.0"></a>
## [v3.7.0] - 2021-03-02

- feat: add S3 import functionality which is supported for MySQL instances ([#197](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/197))
- chore: add ci-cd workflow for pre-commit checks ([#195](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/195))


<a name="v3.6.0"></a>
## [v3.6.0] - 2021-02-20

- chore: update documentation based on latest `terraform-docs` which includes module and resource sections ([#191](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/191))


<a name="v3.5.0"></a>
## [v3.5.0] - 2021-02-14

- feat: Support major version engine upgrades ([#188](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/188))


<a name="v3.4.0"></a>
## [v3.4.0] - 2021-01-20

- fix: Create random_password conditionally ([#184](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/184))


<a name="v3.3.0"></a>
## [v3.3.0] - 2021-01-15

- docs: Update Serverless MySQL/PostgreSQL example ([#95](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/95))


<a name="v3.2.0"></a>
## [v3.2.0] - 2021-01-15

- fix: Added possibility to specify partition used in iam role policy attachment ([#182](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/182))


<a name="v3.1.0"></a>
## [v3.1.0] - 2021-01-15

- fix: Create random_password only when necessary ([#181](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/181))


<a name="v3.0.0"></a>
## [v3.0.0] - 2021-01-04

- feat: Added conditional creation of RDS Aurora cluster ([#180](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/180))


<a name="v2.29.0"></a>
## [v2.29.0] - 2020-10-30

- feat: Added conditional creation of RDS Aurora cluster ([#159](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/159))


<a name="v2.28.0"></a>
## [v2.28.0] - 2020-10-13

- Updated docs
- feat: add output engine_version to force provider order ([#152](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/152))


<a name="v2.27.0"></a>
## [v2.27.0] - 2020-10-07

- feat: Updated pre-commit with tflint ([#150](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/150))
- fix: Ignore instance engine version updates ([#134](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/134))


<a name="v2.26.0"></a>
## [v2.26.0] - 2020-09-22

- feat: Allow to customizable instance settings ([#146](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/146))


<a name="v2.25.0"></a>
## [v2.25.0] - 2020-09-22



<a name="v2.24.0"></a>
## [v2.24.0] - 2020-09-22

- feat: Add support for existing IAM role for enhanced monitoring ([#79](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/79))


<a name="v2.23.0"></a>
## [v2.23.0] - 2020-08-27

- feat: Allows different instance_size for replicas ([#61](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/61))


<a name="v2.22.0"></a>
## [v2.22.0] - 2020-08-19

- feat: Add output aws_rds_cluster.this.hosted_zone_id ([#125](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/125))


<a name="v2.21.0"></a>
## [v2.21.0] - 2020-08-13

- Updated version requirements for AWS provider v3


<a name="v2.20.0"></a>
## [v2.20.0] - 2020-07-20

- feat: Add tags to RDS enhanced monitoring IAM role ([#136](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/136))
- Upgraded Terraform version supported


<a name="v2.19.0"></a>
## [v2.19.0] - 2020-06-12

- feat: add "this_rds_cluster_instance_ids" to module outputs ([#107](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/107))
- docs: Add "multimaster" to engine_mode docs ([#133](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/133))


<a name="v2.18.0"></a>
## [v2.18.0] - 2020-06-10

- feat: Add permissions boundary for IAM role ([#104](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/104))
- Updated README


<a name="v2.17.0"></a>
## [v2.17.0] - 2020-04-11

- feat: Support enable_http_endpoint - Data API ([#117](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/117))
- Updated postgres example to latest engine_version


<a name="v2.16.0"></a>
## [v2.16.0] - 2020-02-26

- Updated pre-commit-terraform with README
- Updated pre-commit-terraform with README
- Adding support for ca_cert_identifier for the upcoming RDS cert update on 5 March 2020 ([#91](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/91)) ([#98](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/98))
- Added missing type type for allowed_security_groups variable ([#97](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/97))


<a name="v2.15.0"></a>
## [v2.15.0] - 2020-01-28

- Disabled special characters in random_password ([#101](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/101))


<a name="v2.14.0"></a>
## [v2.14.0] - 2020-01-23

- Changed random_id to random_password resource ([#99](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/99))


<a name="v2.13.0"></a>
## [v2.13.0] - 2020-01-23

- Adding version requirements


<a name="v2.12.0"></a>
## [v2.12.0] - 2020-01-23

- Updated pre-commit-terraform to support terraform-docs 0.8
- Hide sensitive password data from cli output ([#89](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/89))


<a name="v2.11.0"></a>
## [v2.11.0] - 2019-11-29

- Made description of security group backward compatible (and optional) ([#87](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/87))
- Add security group name and description ([#80](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/80))
- Updated README
- Set null as default db_parameter_group_name ([#72](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/72))
- Support setting aws_rds_cluster iam roles ([#74](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/74))
- Fix the error when "create_security_group" is false ([#75](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/75))
- Added support for conditional creation of SG and allowed CIDR blocks ([#71](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/71))
- Updated README
- Add option to customise predefined_metric_type ([#66](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/66))
- Added support for backtrack_window, cross region read replicas, copy_tags_to_snapshots, scaling_configurations ([#70](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/70))
- Fixes after [#64](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/64) (subnets are optional now), updated pre-commit hooks and docs
- Add support to use existing subnet group name ([#64](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/64))
- Fix PostgreSQL example link ([#52](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/52))
- Support using previously created SG for Aurora cluster - TF 0.12 ([#49](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/49))
- Add cluster ARN output as 'this_rds_cluster_arn' ([#48](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/48))
- Upgraded module to support Terraform 0.12 ([#45](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/45))

###

on ../../modules/aws-rds-aurora/main.tf line 4, in locals:

4:   db_subnet_group_name = var.db_subnet_group_name == "" ?
aws_db_subnet_group.this[0].name : var.db_subnet_group_name

|----------------

| aws_db_subnet_group.this is empty tuple

when calling import with this module in the configuration.


<a name="v1.21.0"></a>
## [v1.21.0] - 2019-11-28

- Revert "add support for ca_cert_identifier option ([#83](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/83))" ([#85](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/85))
- add support for ca_cert_identifier option ([#83](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/83))
- Updated docs
- Add scaling_configuration ([#63](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/63))
- Added ability to deploy a cross region Aurora Cluster Read Replica ([#69](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/69))
- Added backtrack_windows for Aurora ([#57](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/57))
- Added changelog
- Added copy_tags_to_snapshot (closes [#60](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/60))
- Allow the addition of IP-based ingress rules ([#51](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/51))
- vpc_security_group_ids for Terraform 0.11 ([#46](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/46))


<a name="v2.10.0"></a>
## [v2.10.0] - 2019-11-28

- Add security group name and description ([#80](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/80))
- Updated README
- Set null as default db_parameter_group_name ([#72](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/72))
- Support setting aws_rds_cluster iam roles ([#74](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/74))
- Fix the error when "create_security_group" is false ([#75](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/75))
- Added support for conditional creation of SG and allowed CIDR blocks ([#71](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/71))
- Updated README
- Add option to customise predefined_metric_type ([#66](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/66))
- Added support for backtrack_window, cross region read replicas, copy_tags_to_snapshots, scaling_configurations ([#70](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/70))
- Fixes after [#64](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/64) (subnets are optional now), updated pre-commit hooks and docs
- Add support to use existing subnet group name ([#64](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/64))
- Fix PostgreSQL example link ([#52](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/52))
- Support using previously created SG for Aurora cluster - TF 0.12 ([#49](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/49))
- Add cluster ARN output as 'this_rds_cluster_arn' ([#48](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/48))
- Upgraded module to support Terraform 0.12 ([#45](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/45))

###

on ../../modules/aws-rds-aurora/main.tf line 4, in locals:

4:   db_subnet_group_name = var.db_subnet_group_name == "" ?
aws_db_subnet_group.this[0].name : var.db_subnet_group_name

|----------------

| aws_db_subnet_group.this is empty tuple

when calling import with this module in the configuration.


<a name="v1.20.0"></a>
## [v1.20.0] - 2019-11-28

- add support for ca_cert_identifier option ([#83](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/83))
- Updated docs
- Add scaling_configuration ([#63](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/63))
- Added ability to deploy a cross region Aurora Cluster Read Replica ([#69](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/69))
- Added backtrack_windows for Aurora ([#57](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/57))
- Added changelog
- Added copy_tags_to_snapshot (closes [#60](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/60))
- Allow the addition of IP-based ingress rules ([#51](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/51))
- vpc_security_group_ids for Terraform 0.11 ([#46](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/46))


<a name="v2.9.0"></a>
## [v2.9.0] - 2019-11-08

- Updated README
- Set null as default db_parameter_group_name ([#72](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/72))


<a name="v2.8.0"></a>
## [v2.8.0] - 2019-11-08

- Support setting aws_rds_cluster iam roles ([#74](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/74))


<a name="v2.7.0"></a>
## [v2.7.0] - 2019-11-08

- Fix the error when "create_security_group" is false ([#75](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/75))


<a name="v2.6.0"></a>
## [v2.6.0] - 2019-09-30

- Added support for conditional creation of SG and allowed CIDR blocks ([#71](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/71))


<a name="v2.5.0"></a>
## [v2.5.0] - 2019-09-30

- Updated README
- Add option to customise predefined_metric_type ([#66](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/66))


<a name="v2.4.0"></a>
## [v2.4.0] - 2019-09-30

- Added support for backtrack_window, cross region read replicas, copy_tags_to_snapshots, scaling_configurations ([#70](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/70))
- Fixes after [#64](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/64) (subnets are optional now), updated pre-commit hooks and docs
- Add support to use existing subnet group name ([#64](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/64))
- Fix PostgreSQL example link ([#52](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/52))
- Support using previously created SG for Aurora cluster - TF 0.12 ([#49](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/49))
- Add cluster ARN output as 'this_rds_cluster_arn' ([#48](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/48))
- Upgraded module to support Terraform 0.12 ([#45](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/45))


<a name="v1.19.0"></a>
## [v1.19.0] - 2019-09-29

- Updated docs
- Add scaling_configuration ([#63](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/63))


<a name="v1.18.0"></a>
## [v1.18.0] - 2019-09-29

- Added ability to deploy a cross region Aurora Cluster Read Replica ([#69](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/69))


<a name="v1.17.0"></a>
## [v1.17.0] - 2019-09-28

- Added backtrack_windows for Aurora ([#57](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/57))


<a name="v1.16.0"></a>
## [v1.16.0] - 2019-09-28

- Added changelog
- Added copy_tags_to_snapshot (closes [#60](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/60))
- Allow the addition of IP-based ingress rules ([#51](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/51))
- vpc_security_group_ids for Terraform 0.11 ([#46](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/46))


<a name="v2.3.0"></a>
## [v2.3.0] - 2019-08-29

- Fixes after [#64](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/64) (subnets are optional now), updated pre-commit hooks and docs
- Add support to use existing subnet group name ([#64](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/64))
- Fix PostgreSQL example link ([#52](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/52))


<a name="v2.2.0"></a>
## [v2.2.0] - 2019-06-24

- Support using previously created SG for Aurora cluster - TF 0.12 ([#49](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/49))
- Add cluster ARN output as 'this_rds_cluster_arn' ([#48](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/48))
- Upgraded module to support Terraform 0.12 ([#45](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/45))


<a name="v1.15.0"></a>
## [v1.15.0] - 2019-06-24

- Allow the addition of IP-based ingress rules ([#51](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/51))
- vpc_security_group_ids for Terraform 0.11 ([#46](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/46))


<a name="v2.1.0"></a>
## [v2.1.0] - 2019-06-14

- Add cluster ARN output as 'this_rds_cluster_arn' ([#48](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/48))
- Upgraded module to support Terraform 0.12 ([#45](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/45))


<a name="v1.14.0"></a>
## [v1.14.0] - 2019-06-13

- vpc_security_group_ids for Terraform 0.11 ([#46](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/46))


<a name="v2.0.0"></a>
## [v2.0.0] - 2019-06-11

- Upgraded module to support Terraform 0.12 ([#45](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/45))


<a name="v1.13.0"></a>
## [v1.13.0] - 2019-04-25

- Fixed formatting
- Remove unused variable identifier_prefix ([#36](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/36))
- Correct description of replica_scale_min variable ([#37](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/37))


<a name="v1.12.0"></a>
## [v1.12.0] - 2019-03-22

- Fix formatting
- Feature/rds cluster resource id output ([#31](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/31))


<a name="v1.11.0"></a>
## [v1.11.0] - 2019-03-22

- Fix formatting and string variables
- add engine_mode and global_cluster_identifier ([#32](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/32))


<a name="v1.10.0"></a>
## [v1.10.0] - 2019-02-28

- Fixed readme
- add enabled_cloudwatch_logs_exports ([#29](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/29))


<a name="v1.9.0"></a>
## [v1.9.0] - 2019-02-16

- Remove validation
- Add support for IAM Database authentication


<a name="v1.8.0"></a>
## [v1.8.0] - 2019-01-31

- Updated example with correct allowed_security_groups_count
- Run pre-commit hooks
- Hardcode number of allowed_security_groups


<a name="v1.7.0"></a>
## [v1.7.0] - 2019-01-30

- Removing myself from README


<a name="v1.6.0"></a>
## [v1.6.0] - 2019-01-30

- Merge remote-tracking branch 'origin/master' into pr-13
- Added output for database_name
- add support for database_name argument


<a name="v1.5.0"></a>
## [v1.5.0] - 2019-01-30

- Merge branch 'master' into support_deletion_protection
- Added argument deletion_protection


<a name="v1.4.0"></a>
## [v1.4.0] - 2019-01-30

- Removed availability_zones var (closes [#10](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/issues/10))


<a name="v1.3.0"></a>
## [v1.3.0] - 2019-01-30

- Run pre-commit hooks
- Merge branch 'master' into fix_az
- Fixed variable for az


<a name="v1.1.0"></a>
## [v1.1.0] - 2019-01-30

- Run pre-commit hooks
- 3 adjustments: - Avoid description attr on aws_security_group to avoid forcing new instance on changes - Use name-prefix to ensure unique names - Avoid unnecessary name-prefixes


<a name="v1.0.0"></a>
## [v1.0.0] - 2018-12-11

- Updated pre-commit hooks version
- Fix for: 'count' cannot be computed
- Added few files
- Made small changes to be closer to other terraform-aws-modules
- adding pre commit hooks config
- updating readme, docs, main.tf etc
- adding port output
- adding 3 examples
- Removing route53 record and all monitoring as requested
- many fixes and changes
- Initial commit


<a name="v0.0.1"></a>
## v0.0.1 - 2017-09-26

- Initial commit
- Initial commit


[Unreleased]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v6.1.0...HEAD
[v6.1.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v6.0.0...v6.1.0
[v6.0.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v5.3.0...v6.0.0
[v5.3.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v5.2.0...v5.3.0
[v5.2.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v5.1.0...v5.2.0
[v5.1.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v5.0.0...v5.1.0
[v5.0.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v4.3.0...v5.0.0
[v4.3.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v4.2.0...v4.3.0
[v4.2.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v4.1.0...v4.2.0
[v4.1.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v4.0.0...v4.1.0
[v4.0.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.13.0...v4.0.0
[v3.13.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.12.0...v3.13.0
[v3.12.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.11.0...v3.12.0
[v3.11.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.10.0...v3.11.0
[v3.10.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.9.0...v3.10.0
[v3.9.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.8.0...v3.9.0
[v3.8.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.7.0...v3.8.0
[v3.7.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.6.0...v3.7.0
[v3.6.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.5.0...v3.6.0
[v3.5.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.4.0...v3.5.0
[v3.4.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.3.0...v3.4.0
[v3.3.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.2.0...v3.3.0
[v3.2.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.1.0...v3.2.0
[v3.1.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v3.0.0...v3.1.0
[v3.0.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.29.0...v3.0.0
[v2.29.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.28.0...v2.29.0
[v2.28.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.27.0...v2.28.0
[v2.27.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.26.0...v2.27.0
[v2.26.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.25.0...v2.26.0
[v2.25.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.24.0...v2.25.0
[v2.24.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.23.0...v2.24.0
[v2.23.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.22.0...v2.23.0
[v2.22.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.21.0...v2.22.0
[v2.21.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.20.0...v2.21.0
[v2.20.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.19.0...v2.20.0
[v2.19.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.18.0...v2.19.0
[v2.18.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.17.0...v2.18.0
[v2.17.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.16.0...v2.17.0
[v2.16.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.15.0...v2.16.0
[v2.15.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.14.0...v2.15.0
[v2.14.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.13.0...v2.14.0
[v2.13.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.12.0...v2.13.0
[v2.12.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.11.0...v2.12.0
[v2.11.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.21.0...v2.11.0
[v1.21.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.10.0...v1.21.0
[v2.10.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.20.0...v2.10.0
[v1.20.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.9.0...v1.20.0
[v2.9.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.8.0...v2.9.0
[v2.8.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.7.0...v2.8.0
[v2.7.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.6.0...v2.7.0
[v2.6.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.5.0...v2.6.0
[v2.5.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.4.0...v2.5.0
[v2.4.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.19.0...v2.4.0
[v1.19.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.18.0...v1.19.0
[v1.18.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.17.0...v1.18.0
[v1.17.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.16.0...v1.17.0
[v1.16.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.3.0...v1.16.0
[v2.3.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.2.0...v2.3.0
[v2.2.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.15.0...v2.2.0
[v1.15.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.1.0...v1.15.0
[v2.1.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.14.0...v2.1.0
[v1.14.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v2.0.0...v1.14.0
[v2.0.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.13.0...v2.0.0
[v1.13.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.12.0...v1.13.0
[v1.12.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.11.0...v1.12.0
[v1.11.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.10.0...v1.11.0
[v1.10.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.9.0...v1.10.0
[v1.9.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.8.0...v1.9.0
[v1.8.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.7.0...v1.8.0
[v1.7.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.6.0...v1.7.0
[v1.6.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.5.0...v1.6.0
[v1.5.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.4.0...v1.5.0
[v1.4.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.3.0...v1.4.0
[v1.3.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.1.0...v1.3.0
[v1.1.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v1.0.0...v1.1.0
[v1.0.0]: https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/compare/v0.0.1...v1.0.0
