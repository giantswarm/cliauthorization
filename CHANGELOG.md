# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).



## [Unreleased]

- Replace `github.com/form3tech-oss/jwt-go` with `github.com/golang-jwt/jwt`

## [0.2.4] - 2021-05-04

### Changed

- Use fork of `jwt-go` library to fix CVE related to audience handling.

## [0.2.3] - 2020-09-04

- Add InitializeWithLogger function to enable custom logging target

## [0.2.2] - 2020-08-20

- Increase resiliency using custom endpoints in `ChooseEndpoint`, `ChooseScheme`, `ChooseToken` and `SetProvider`
- When using custom endpoints, unknown endpoint configurations will not be persisted in the config file anymore
- When using custom endpoints, the custom endpoint will not be selected anymore

## [0.2.1] 2020-04-22

- Remove email from the selected endpoint and endpoint list after logging out




## [0.2.0] 2020-04-10

- Switch from dep to Go modules.



## [0.1.0] 2020-01-16

### Added

- First release.



[Unreleased]: https://github.com/giantswarm/gscliauth/compare/v0.2.4...HEAD
[0.2.4]: https://github.com/giantswarm/gscliauth/compare/v0.2.3...v0.2.4
[0.2.3]: https://github.com/giantswarm/gscliauth/compare/v0.2.2...v0.2.3
[0.2.2]: https://github.com/giantswarm/gscliauth/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/giantswarm/gscliauth/compare/v0.2.0...v0.2.1

[0.2.0]: https://github.com/giantswarm/gscliauth/compare/v0.1.0...v0.2.0

[0.1.0]: https://github.com/giantswarm/gscliauth/releases/tag/v0.1.0
