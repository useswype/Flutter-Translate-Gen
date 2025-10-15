## 1.0.0

- Initial release

## 1.1.0

- Implemented multiple case style options

## 1.2.0

- Added support for pluralization
- '0', '1' and 'else' are now reserved words 

## 1.2.4

- Fixed dependency compatibility issues

## 1.3.0

- Upgraded dependencies

## 2.0.0

- Upgraded dependencies

## 2.1.0

- Added camel case support

## 2.2.0

- Upgraded dependencies

## [4.0.0]

### Breaking Changes
- **Requires Dart SDK >= 3.0.0** - Dropped support for Dart 2.x
- Updated minimum SDK constraint from `>=2.12.0 <3.0.0` to `>=3.0.0 <4.0.0`

### Changed
- Updated `build` to ^4.0.2 (from ^3.0.2)
- Updated `source_gen` to ^4.0.2 (from ^3.1.0)
- Updated `build_runner` to ^2.4.15 (from ^2.1.10)
- Updated `code_builder` to ^4.11.0 (from ^4.10.1)

### Fixed
- Removed unreachable default clause in switch statement for Dart 3 compatibility
- Fixed analyzer warnings for exhaustive switch statements
