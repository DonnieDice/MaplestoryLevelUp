# Changelog

## [3.0.4] - 2026-04-15

### Changed
- Version dynamically pulled from TOC using `GetAddOnMetadata`
- Improved localization safety checks to prevent nil reference errors

### Fixed
- Added guard clauses for `self.L` references in `DisplayWelcomeMessage()`, `HandleSlashCommand()`, and `ShowHelp()` functions
- Consistent version across all TOC files (Retail, TBC, Vanilla, Wrath)
