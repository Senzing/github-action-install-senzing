# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog],
[markdownlint],
and this project adheres to [Semantic Versioning].

## [Unreleased]

-

## [5.0.0] - 2024-11-12

### Changed in 5.0.0

- Restrict this action to Senzing API installs V3 and lower.

## [3.0.2] - 2024-08-20

### Changed in 3.0.2

- Backwards compatibility for versions < 4.

## [3.0.1] - 2024-08-14

### Changed in 3.0.1

- Change references of `g2` to `sz` for filename prefixes and `er` for directory names.

## [3.0.0] - 2024-04-12

### Changed in 3.0.0

- Switch linux install package from `senzingapi` to `senzingapi-runtime`.

## [2.0.0] - 2024-02-28

### Changed in 2.0.0

- Add support for all versions of `senzingapi`.
- Switch `latest` to `production`.
- Require major version specification.

## [1.2.3] - 2023-10-05

### Changed in 1.2.3

- Updated `apt` staging URL to `https://senzing-staging-apt.s3.amazonaws.com/senzingstagingrepo_1.0.1-1_all.deb`
- Updated `apt` production URL to `https://senzing-production-apt.s3.amazonaws.com/senzingrepo_1.0.1-1_all.deb`

## [1.2.2] - 2023-09-27

### Changed in 1.2.2

- Updated URLs to Senzing artifacts

## [1.2.1] - 2023-09-07

### Added to 1.2.1

- Refactor code for easier maintenance.

## [1.2.0] - 2023-09-05

### Added to 1.2.0

- Support for `with.senzingapi-version` for `latest`, `staging`, and Senzing API versions.

## [1.1.1] - 2023-09-01

### Added to 1.1.1

- Updated to SenzingAPI 3.8.0

## [1.1.0] - 2023-08-23

### Added to 1.1.0

- Support for `@latest` tag

## [1.0.0] - 2023-08-23

### Added to 1.0.0

- Install Senzing API on Linux, macOS, and Windows

[Keep a Changelog]: https://keepachangelog.com/en/1.0.0/
[markdownlint]: https://dlaa.me/markdownlint/
[Semantic Versioning]: https://semver.org/spec/v2.0.0.html
