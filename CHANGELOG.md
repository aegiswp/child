# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.4] - 2026-10-27

### Changed

- Aligned WordPress and PHP compatibility headers with the Aegis parent theme (`Requires at least: 7.0`, `Tested up to: 7.1.3`, PHP 8.1).
- Updated `theme.json` `$schema` to `https://schemas.wp.org/wp/7.1/theme.json`.

### Added

- Root `CHANGELOG.md` for Keep a Changelog tracking alongside `README.md` / `readme.txt`.

## [1.0.3] - 2026-05-04

### Changed

- Clarified parent-child loading requirements, including the `Template: aegis` directory dependency (`/wp-content/themes/aegis`).
- Expanded installation and usage documentation to describe block theme inheritance and child override behavior.
- Updated theme package metadata to version 1.0.3 and aligned minimum PHP to 8.1.
- Aligned licensing with the parent theme (GNU GPL v2 or later) across headers, package metadata, docs, and LICENSE text.

### Added

- Root theme compatibility file (`index.php`) guidance for distribution expectations.

## [1.0.2] - 2026-01-19

### Added

- GitHub Actions workflow for automated releases.

### Changed

- Updated theme branding and description.
- Documentation improvements.

## [1.0.1] - 2025-07-11

### Changed

- Set the version number to 1.0.1.

## [1.0.0] - 2023-11-01

### Added

- Initial release.
