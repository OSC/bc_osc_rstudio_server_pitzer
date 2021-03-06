# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
## [0.4.0] - 2020-08-28
### Changed
- This app now raises an exception when trying to submit with the addition of
  [#6](https://github.com/OSC/bc_osc_rstudio_server_pitzer/pull/6). This is because
  we now have functionality to submit to multiple clusters and 
  [the generic application](https://github.com/OSC/bc_osc_rstudio_server) now submits
  to pitzer.


## [0.3.0] - 2020-07-31
### Added
- Added R module 4.0.2

## [0.2.0] - 2020-05-21
### Changed
- removed the way env gets written and read, this can be shown to be unstable.

### Added
- loads R_LIBS_SITE environment variable if it is set.
- Added R 3.6.3.
- Added the ability to schedule on GPUs (but only for R/3.6.3).

## [0.1.5] - 2020-01-06
### Fixed
- Remove incorrect Singularity image
- Add missing module for R/3.6.0

## [0.1.4] - 2019-12-20
### Fixed
- Fix breaking changes with the way Singularity 3.5.x handles environment variables

## [0.1.3] - 2019-10-11
### Changed
- Removed hardcoded fix that shadowed the module variables

## [0.1.2] - 2019-10-10
### Fixed
- Fixed crash relating to missing `/apps` in bind mount

## [0.1.1] - 2019-10-10
### Fixed
- Fixed crash relating to duplicate bind mounts including `/etc` caused by OSC `singularity.conf`

## [0.1.0] - 2019-13-08
### Added
- Added R 3.6.0

## [0.0.2] - 2019-09-07
### Added
- Added xalt

## [0.0.1] - 2019-21-03
### Added
- Initial release!

[Unreleased]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.4.0...HEAD
[0.4.0]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.1.5...v0.2.0
[0.1.5]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.1.4...v0.1.5
[0.1.4]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.0.2...v0.1.0
[0.0.2]: https://github.com/OSC/bc_osc_rstudio_server/compare/v0.0.1...v0.0.2
