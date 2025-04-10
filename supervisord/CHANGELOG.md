# CHANGELOG - supervisord

## 1.7.1 / 2021-03-07 / Agent 7.27.0

* [Fixed] Bump minimum base package version. See [#8443](https://github.com/DataDog/integrations-core/pull/8443).

## 1.7.0 / 2020-10-31 / Agent 7.24.0

* [Added] [doc] Add encoding in log config sample. See [#7708](https://github.com/DataDog/integrations-core/pull/7708).
* [Added] Add supervisord logs. See [#7636](https://github.com/DataDog/integrations-core/pull/7636).

## 1.6.1 / 2020-09-21 / Agent 7.23.0

* [Fixed] Fix style for the latest release of Black. See [#7438](https://github.com/DataDog/integrations-core/pull/7438).

## 1.6.0 / 2020-05-17 / Agent 7.20.0

* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).

## 1.5.0 / 2020-04-04 / Agent 7.19.0

* [Added] Make error message more explicit. See [#6211](https://github.com/DataDog/integrations-core/pull/6211).
* [Added] Enable basic authentication for socket option (unix_http_server). See [#6239](https://github.com/DataDog/integrations-core/pull/6239).
* [Fixed] Update deprecated imports. See [#6088](https://github.com/DataDog/integrations-core/pull/6088).

## 1.4.0 / 2020-02-22 / Agent 7.18.0

* [Added] Upgrade supervisor dependency. See [#5627](https://github.com/DataDog/integrations-core/pull/5627).

## 1.3.0 / 2019-12-02 / Agent 7.16.0

* [Added] Add version metadata. See [#4979](https://github.com/DataDog/integrations-core/pull/4979).

## 1.2.0 / 2019-05-14 / Agent 6.12.0

* [Added] Support Python 3. See [#3605](https://github.com/DataDog/integrations-core/pull/3605).
* [Added] Adhere to code style. See [#3571](https://github.com/DataDog/integrations-core/pull/3571).

## 1.1.4 / 2018-10-29 / Agent 6.8.0

* [Fixed] Fix AgentCheck import. See [#2482][1].

## 1.1.3 / 2018-09-04 / Agent 6.5.0

* [Fixed] Add data files to the wheel package. See [#1727][2].

## 1.1.2 / 2018-06-20 / Agent 6.4.0

* [Tooling] Bump check to be in sync with new release tooling

## 1.1.1 / 2018-01-10

* [FEATURE] add support for tags per instance. See [#411][3]. Thanks [@frederikhappel][4].

## 1.1.0 / 2017-09-18

* [SECURITY] bumping supervisor dep to 3.3.3 to address [CVE-2017-11610][5].

## 1.0.0 / 2017-03-22

* [FEATURE] adds supervisord integration.
[1]: https://github.com/DataDog/integrations-core/pull/2482
[2]: https://github.com/DataDog/integrations-core/pull/1727
[3]: https://github.com/DataDog/integrations-core/pull/411
[4]: https://github.com/frederikhappel
[5]: https://nvd.nist.gov/vuln/detail/CVE-2017-11610
