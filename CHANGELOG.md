# Changelog for the Thoth common module

## [0.2.1] - 2018-Jul-10 - goern

### Fixed

- some minor syntax error ;)

## [0.2.0] - 2018-Jul-09 - goern

### Fixed

- https://github.com/thoth-station/result-api/issues/39

## [0.1.0] - 2018-Jul-06 - goern

### Changed

Nothing, just to bounce from 0.0.9 to 0.1.0

## [0.0.9] - 2018-Jun-28 - goern

### Fixed

- argument name in logger_setup() see https://github.com/thoth-station/common/pull/31

## [0.0.8] - 2018-Jun-25 - goern

### Added

Starting with this release we have a Zuul-CI pipeline that:

- lints on Pull Requrest and gate/merge
- uploads to pypi (test) on tag

## Release 0.2.6 (2018-09-03T09:48:51)


## Release 0.2.7 (2018-09-03T13:53:07)


## Release 0.3.0 (2018-09-05T12:27:24)
* Let's reuse adviser env var names
* Issue warning on suspicious parameter expansion in templates
* Fix propagating debug flag to package-extract
* Fix gathering pod logs for default middletier namespace
* Fix gathering pod status for default middletier namespace
* Automatic update of dependency pytest-cov from 2.5.1 to 2.6.0
* Introduce routine for running provenance checker

## Release 0.3.1 (2018-09-17T07:39:06)
* added github configuration
* Automatic update of dependency pytest from 3.7.4 to 3.8.0
* Fix built-in type shadowing