# Changelog

Framesync adheres to [Semantic Versioning](http://semver.org/).

## [3.1.8] 2018-05-13

### Added

- Rollup support for outputting ES modules and UMD bundles.

## [3.1.7] 2018-01-04

### Fixed

- Fixing illegal invocation errors.

## [3.1.6] 2018-01-04

### Changed

- Using previous frame duration as default duration (for instance between active cycles).

## [3.1.5] 2018-01-04

### Changed

- Cleaning polyfill.

## [3.1.4] 2018-01-04

### Changed

- Max permitted time elapsed is now 40ms to permit 30fps max.
- When `startRenderLoop` is fired, and the loop is not active, we set a new `currentTime`.

## [3.1.3] 2017-11-08

### Fixed

- Actually pointing to new declaration file.

## [3.1.2] 2017-11-08

### Fixed

- Pointing to new declaration file.

## [3.1.1] 2017-11-08

### Fixed

- Automatically exporting declaration file.

## [3.1.0] 2017-11-08

### Added

- Added optional `true` flag to `schedule`. This will schedule a job to run at the end of the current frame step.

## [3.0.0] 2017-08-28

- `currentFrameTimestamp` becomes `currentFrameTime` for symmetry with `currentTime`.

## [2.0.1] 2017-08-26

### Added
- Changelog and Readme.

## [2.0.0] 2017-08-26

### Added
- First publish.
