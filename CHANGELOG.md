## [1.5.0]

### Added
 - Add API to set vtag in connection call.
 - CMake: add secure compile flags.

## [1.4]

### Added
 - Add option to log to syslog (use USE_SYSLOG parameter in CMake).

### Changed

### Fixed
 - Cleanup code.
 - Use symbolic constants to improve code readability.
 - Use O_CLOEXEC when opening device file.

## [1.3]

### Added

 - Add configuration files for gitlint, cmake-format.
 - Add internal checkpatch.pl from the Linux kernel.
 - Add API to utilize already open file handle.

### Changed

1. CMake cleanups.

### Fixed

1. Account to strdup failure in init.
2. Fix a typo in enum.
3. dump_hex_buffer() remove variable length array.

## [1.2]

### Added

 - Add mei_fwstatus API to obtain FW status.
 - Add static library build.
 - Add compiler security hardening flags.

### Changed
 - Set default device to mei0.

### Fixed

## [1.0]

### Added

### Changed

### Fixed