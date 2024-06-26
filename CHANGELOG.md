# New Relic Kafka Connect Sink Connector Release Notes #

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## 2.3.3 (2024-04-10)
### Changed
 - Updated [Telemetry SDK](https://github.com/newrelic/newrelic-telemetry-sdk-java) to 0.16.0 (CVE-2023-3635)

## 2.3.2 (2022-10-24)
### Changed
 - Updated jackson-databind to 2.13.4.2 (CVE-2022-42003,CVE-2022-42004)

## 2.3.1 (2022-09-20)
### Changed
 - Updated [Telemetry SDK](https://github.com/newrelic/newrelic-telemetry-sdk-java) version to 0.15
 - Updated jackson-databind to 2.12.6.1
 - Updated junit to 4.13.1
 - Updated slf4j-api to 1.7.36

## 2.3.0 (2022-05-09)
### Added
- Added new `nr.region` parameter to specify the New Relic data region. Default is `US`.

### Changed
 - Updating [Telemetry SDK](https://github.com/newrelic/newrelic-telemetry-sdk-java) version to 0.13.1

## 1.1.0 (2021-04-14)
### Added
- Adding new Logs Sink Connector for sending Kafka messages to New Relic Logs.
- Added new `nr.timeout` parameter for all connectors. Default is 2 seconds.

### Changed
 - Updating [Telemetry SDK](https://github.com/newrelic/newrelic-telemetry-sdk-java) version from 0.6.0 to 0.12.0
 - Added simple [GitHub action](https://github.com/newrelic/kafka-connect-newrelic/actions) that runs tests on commits and PR's

## 1.0.0 (2020-09-30)
### Added
- Initial version
