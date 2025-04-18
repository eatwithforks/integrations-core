# CHANGELOG - Openstack_controller

## 1.11.0 / 2021-04-19

* [Added] Openstack controller log support. See [#9115](https://github.com/DataDog/integrations-core/pull/9115).
* [Fixed] Fix refactored imports. See [#9136](https://github.com/DataDog/integrations-core/pull/9136).
* [Fixed] Add config spec for Openstack Controller. See [#9092](https://github.com/DataDog/integrations-core/pull/9092).

## 1.10.3 / 2021-02-11 / Agent 7.27.0

* [Fixed] Remove SimpleApi cache. See [#8583](https://github.com/DataDog/integrations-core/pull/8583).
* [Fixed] Bump minimum base package version. See [#8443](https://github.com/DataDog/integrations-core/pull/8443).

## 1.10.2 / 2020-09-21 / Agent 7.23.0

* [Fixed] Fix style for the latest release of Black. See [#7438](https://github.com/DataDog/integrations-core/pull/7438).

## 1.10.1 / 2020-08-10 / Agent 7.22.0

* [Fixed] Update ntlm_domain example. See [#7118](https://github.com/DataDog/integrations-core/pull/7118).

## 1.10.0 / 2020-06-29 / Agent 7.21.0

* [Added] Add note about warning concurrency. See [#6967](https://github.com/DataDog/integrations-core/pull/6967).

## 1.9.0 / 2020-05-17 / Agent 7.20.0

* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).

## 1.8.1 / 2020-02-25 / Agent 7.18.0

* [Fixed] Bump datadog_checks_base dependency to 11.0.0. See [#5838](https://github.com/DataDog/integrations-core/pull/5838).

## 1.8.0 / 2020-02-22

* [Added] Refactor traced decorator and remove wrapt import. See [#5586](https://github.com/DataDog/integrations-core/pull/5586).

## 1.7.0 / 2020-01-13 / Agent 7.17.0

* [Added] Use lazy logging format. See [#5398](https://github.com/DataDog/integrations-core/pull/5398).
* [Added] Use lazy logging format. See [#5377](https://github.com/DataDog/integrations-core/pull/5377).

## 1.6.0 / 2019-10-11 / Agent 6.15.0

* [Added] Add option to override KRB5CCNAME env var. See [#4578](https://github.com/DataDog/integrations-core/pull/4578).

## 1.5.1 / 2019-08-30 / Agent 6.14.0

* [Fixed] Update class signature to support the RequestsWrapper. See [#4469](https://github.com/DataDog/integrations-core/pull/4469).

## 1.5.0 / 2019-08-24

* [Added] Add requests wrapper to openstack_controller. See [#4365](https://github.com/DataDog/integrations-core/pull/4365).
* [Added] Deployment environment with Terraform. See [#4039](https://github.com/DataDog/integrations-core/pull/4039).

## 1.4.0 / 2019-07-12 / Agent 6.13.0

* [Added] Retrieve floating IPs from network quotas. See [#4079](https://github.com/DataDog/integrations-core/pull/4079).

## 1.3.0 / 2019-07-09

* [Added] Make keystone_server_url config optional in openstack_controller config. See [#3920](https://github.com/DataDog/integrations-core/pull/3920).
* [Added] Openstack: introduce artificial metric in controller to distinguish from legacy integration. See [#4036](https://github.com/DataDog/integrations-core/pull/4036).

## 1.2.1 / 2019-06-01 / Agent 6.12.0

* [Fixed] Fix code style. See [#3838](https://github.com/DataDog/integrations-core/pull/3838).
* [Fixed] Sanitize external host tags. See [#3792](https://github.com/DataDog/integrations-core/pull/3792).

## 1.2.0 / 2019-05-14

* [Added] Adhere to code style. See [#3551](https://github.com/DataDog/integrations-core/pull/3551).

## 1.1.2 / 2019-04-15

* [Fixed] Get details for both private and public flavors. See [#3621](https://github.com/DataDog/integrations-core/pull/3621).

## 1.1.1 / 2019-03-21 / Agent 6.11.0

* [Fixed] Fix issue with exception handling preventing re-authentication in case of token expiration. See [#3321](https://github.com/DataDog/integrations-core/pull/3321).

## 1.1.0 / 2019-03-15

* [Added] Add project tags to hypervisor metrics. See [#3277](https://github.com/DataDog/integrations-core/pull/3277).
* [Fixed] Fix pagination logic when making request to get servers/flavors details. See [#3301](https://github.com/DataDog/integrations-core/pull/3301).
* [Added] Add openstacksdk option to openstack_controller. See [#3109](https://github.com/DataDog/integrations-core/pull/3109).
* [Fixed] Refactor openstack_controller check api and back caches. See [#3142](https://github.com/DataDog/integrations-core/pull/3142).

## 1.0.1 / 2019-02-18 / Agent 6.10.0

* [Fixed] Refactor openstack_controller check cache. See [#3120](https://github.com/DataDog/integrations-core/pull/3120).

## 1.0.0 / 2019-02-04

* [Added] OpenStack Controller. See [#2496](https://github.com/DataDog/integrations-core/pull/2496).
