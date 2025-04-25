# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),  
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.2] - 2025-04-25

### Changed

- Removed PSR-4 autoloading and PHP class-based preset
- Migrated to JSON-based Pint configuration
- Cleaned up composer.json and removed Laravel-specific entries

## [1.0.1] - 2025-04-25

### Fixed

- Corrected package name in pint.json usage documentation
- Resolved issue with undefined array key when using the PHP class preset

## [1.0.0] - 2025-04-25

### Added

- Initial release of the Laravel Pint preset
- Includes opinionated Pint rules for Laravel and PHP projects
- Supports PHP 8.1+ and Laravel Pint 1.10+
