# Changelog
Changes to the project will be tracked in this file via the date of change.

## 2018-10-05
### Changed
- ScanPdf was unintentionally extracting duplicate streams, but now it is fixed to only extract unique streams (Josh Liburdi)

## 2018-10-03
### Added
- ScanJavascript now supports deobfuscating JavaScript files before parsing metadata (Josh Liburdi)

## 2018-09-28
### Added
- ScanUrl now supports user-defined regular expressions that can be called per-file (Josh Liburdi)

### Changed
- Refactored taste.yara `javascript_file` rule for readability (Josh Liburdi)
- Removed JavaScript files from ScanUrl in the default strelka.yml (Josh Liburdi)

## 2018-09-26
### Added
- Project went public!