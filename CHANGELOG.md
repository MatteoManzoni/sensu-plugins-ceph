#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## Unreleased
### Changed
- Upgrade to Rubocop 0.40 and cleanup

### Fixed
- metrics-ceph.rb: Prevent stderr from polluting JSON output (@CoRfr)

## [0.0.5] - 2015-11-26
### Added
- include client name option when interacting with ceph
- metrics script
### Fixes
- use upstram output
- default prefix includes hostname

## [0.0.4] - 2015-07-31
### Changed
- updated documentation links
- updated rubocop to `0.32.1`
- put all deps in alpha order
- removed unused tasks

### Fixed
- health check only runs once on failure with details
- removes processing and conditional over health check result when unnecessary

## [0.0.3] - 2015-07-14

### Changed
- updated sensu-plugin gem to 1.2.0

## 0.0.1 - 2015-04-30

### Added
- initial release

## 0.0.2 - 2015-06-02

### Fixed
- added binstubs

### Changed
- removed cruft from /lib
