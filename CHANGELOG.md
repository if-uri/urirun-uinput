# Changelog

All notable changes to `urirun-uinput` are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/).

## [0.1.0] - 2026-06-26

### Added
- Initial release. The Linux uinput keyboard/mouse input surface primitive
  (key/click/move via `/dev/uinput` ioctls) extracted from
  `urirun.connectors.inputs.uinput` as a standalone, dependency-free package.
- Back-compat: the old import path `urirun.connectors.inputs.uinput` keeps working via a
  `sys.modules` re-export shim in the urirun package.
