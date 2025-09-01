# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## 2025-08-30
- Imported OS Command Injection tests from [Reinforced Wavsep](https://github.com/luigiurbano/Reinforced-Wavsep) at commit [962d566](https://github.com/luigiurbano/Reinforced-Wavsep/commit/962d566ebe51a3f64f772b6c1856d99f1150ba4a).

## 2025-08-28

### Changed
- Main JSP to use leading spaces instead of a mix of spaces and tabs - to make refactoring easier. 

### Fixed
- Changed all of the SQL JSPs to use try-with-resources on the db statement.

## 2025-08-27

### Fixed
- Changed all of the SQL JSPs to use try-with-resources on the db connection.

## 2025-08-08

### Added
- Basic Maven build.
- Docker support.
- Auto initialise DB.
- Simple CI build.

### Changed
- Docs to reflect adoption by ZAP team.

### Fixed
- JSPs to use correct exceptions.

### Removed
- Eclipse files.