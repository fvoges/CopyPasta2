# CopyPasta2 Changelog

All notable changes to this project will be documented in this file.

## [1.0.23](https://github.com/fvoges/CopyPasta2/compare/1.0.22...1.0.23) (2026-04-12)

### Bug Fixes

* **compat:** update settings support for WoW 12.0.1 ([3d0f551](https://github.com/fvoges/CopyPasta2/commit/3d0f5519338b2c1a56df2c0bbc8627872df70ba5))

## [1.0.22] - 2025-01-03

### BREAKING CHANGES

* WoW 11.2.0 deprecated SendChatMessage. All chat message outputs migrated to C_ChatInfo.SendChatMessage for WoW 11.2.5 compatibility. Affected channels: SAY, YELL, PARTY, RAID, INSTANCE_CHAT, GUILD, OFFICER, WHISPER

### Bug Fixes

* **chat:** replace deprecated SendChatMessage with C_ChatInfo API ([66801a4](https://github.com/fvoges/CopyPasta2/commit/66801a4))

### Maintenance

* **release:** add release automation and update for WoW 11.2.5 ([a7d76f6](https://github.com/fvoges/CopyPasta2/commit/a7d76f6))
  - Update Interface version 110200 -> 110205 (WoW 11.2.5)
  - Add Taskfile.yml for automated releases with conventional-changelog
  - Add .clrc for changelog configuration
  - Add .pkgmeta to exclude dev files from packaged releases
  - Replace manual changelog with automated generation

## [1.0.21] - 2024-12-27

### Changed
- Updated Interface version from 110005 to 110200 for WoW 11.0.2+ compatibility

### Documentation
- Rewrote README.md with friendly, welcoming tone
- Added comprehensive installation instructions
- Added feature overview with existing screenshot
- Updated download links to current sources (Wago, GitHub)
- Replaced harsh maintenance notice with community-friendly approach

## [1.0.20] - 2024-11-12

### Fixed
- Fixed GetAddonMetadata API error handling
- Updated interface and addon version for current WoW compatibility

### Changed
- Added fork notification to README.md
- Updated documentation with maintenance approach

## [1.0.10] - 2023-11-10

### Changed
- Updated TOC version for WoW 10.2 Dragonflight compatibility
- Bumped addon version for Dragonflight Season 3 support

## [1.0.9] - 2023-10-17

### Added
- GitHub Actions workflow for automated releases
- BigWigsMods packager integration

### Changed
- Reorganized project structure
- Moved core modules to top-level directory
- Cleaned up legacy code and unused files

## [Pre-1.0.9] - Historical

### Background
- CopyPasta2 is a community-maintained fork of the original CopyPasta addon
- Original addon by Nuaik, based on Paste addon by oscarucb & idlenexusgaming
- Focuses on maintaining WoW compatibility with minimal feature changes
