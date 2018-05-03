# Changelog
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.3.0] - 2018-05-03
### Added
- Support of `firefox-esr-next-latest` and `firefox-esr-next-latest-ssl` aliases


## [1.2.1] - 2018-03-21
### Added
- bouncer aliases preflight checks - making sure the aliases match certain regexes

## [1.1.0] - 2018-03-19
### Changed
- `script.async_main()` relies on scriptworker (>= 10.2.0) to initialize context, config, and task
- `task.validate_task_schema()` now relies on scriptworker

## Removed
- `script.usage()`, now handled by scriptworker
- `task.validate_task_schema()` now handled by scriptworker
- `load_json` now handled by scriptworker (moved it temporarily under tests until integration tests are added)


## [1.0.0] - 2018-03-12
### Added
- changelog
- 100% code-coverage
- production mode for bouncerscript
