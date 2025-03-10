# Changelog

## [0.1.14] - 2025-03-05

### Fixed
- Changed `md2conf` dependency to `markdown-to-confluence`

## [0.1.13] - 2025-03-05

### Fixed
- Added missing `md2conf` dependency to fix ModuleNotFoundError

## [0.1.12] - 2025-03-04

### Added
- Added Confluence page creation and update capabilities with markdown-to-confluence support
- Enhanced resource and tool descriptions with more context and examples

## [0.1.11] - 2025-03-03

### Added
- Added support for setting and updating assignee in Jira issues
- Added Jira comment functionality and enhanced get_issue with comment support
- Enhanced resource filtering to focus on user-contributed content

## [0.1.10] - 2025-02-22

### Added
- Added CLI support with click for configurable server initialization
- Support environment variable loading from .env file
- Implement flexible configuration via command-line options

## [0.1.9] - 2025-02-21

### Added
- Added GitHub Actions workflow for linting
- Added comprehensive test coverage for Confluence and Jira services
- Added new Jira tools: create_issue, update_issue, delete_issue
- Added Cursor IDE configuration documentation

### Changed
- Enhanced Jira issue management methods with improved error handling
- Updated installation instructions with detailed configuration examples

### Fixed
- Fixed URL generation in Confluence methods by removing '/wiki' prefix
- Improved environment variable handling in configuration

## [0.1.8] - 2025-02-16

### Added
- Added Docker support with multi-stage build
- Added Smithery configuration for deployment

### Fixed
- Fixed Jira date parsing for various timezone formats
- Fixed document types import error
- Updated logging configuration

## [0.1.7] - 2024-12-20

### Changed
- Optimized Confluence search performance by removing individual page fetching
- Updated search results format to use pre-generated excerpts

## [0.1.6] - 2025-12-19

### Changed
- Lowered minimum Python version requirement from 3.13 to 3.10 for broader compatibility

## [0.1.5] - 2024-12-19

### Fixed
- Aligned comment metadata keys in Confluence comments endpoint
- Fixed handling of nested structure in Confluence spaces response
- Updated README.md with improved documentation
