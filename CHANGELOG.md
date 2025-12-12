# Changelog

## [1.1.1]

- Updated frontend library

## [1.1.0]

- Added `Create Simulation Launch` to context menu
- Fixed problems with undo/redo
- Fixed several editor bugs
- Fixed using correct defaults
- Reworked region layouting

## [1.0.7]

- Rollback to 1.0.5

## [1.0.6]

- Added `Create Simulation Launch` to context menu
- Fixed problems with undo/redo
- Fixed several editor bugs
- Fixed using correct defaults

## [1.0.5]

- Disable Subdiagrams

## [1.0.4]

- Changed keyword from statemachine to state machine
- Updated frontend library

## [1.0.3]

- Fixed failed simulations running in endless loop
- Added hint for documentation mode in editor
- Added user notification for the remaining days of the subscription
- Fixed using valueof in assignments
- Removed active keyboard shortcuts in read-only mode
- Removed matching parantheses highlighter in editor
- Fixed selecting text for transitions
- Fixed simulation for operations with uppercase

## [1.0.2]

- Fixed marketplace links

## [1.0.1]

- Added categories and keywords

## [1.0.0] - Initial Release

This is the first release of the itemis CREATE extension for Visual Studio Code, which brings the powerful state machine modeling tool, previously available only as an Eclipse-based solution, to the modern and streamlined VS Code environment. The release includes the following key features:

- **Statechart Modeling**: Create and edit statecharts with an intuitive graphical editor.
- **Simulation**: Validate your statechart behavior in real-time.
- **Code Generation**: Generate high-quality code in multiple languages from your models.
- **Examples**: Explore prebuilt examples to understand best practices and use cases.

### Known Issues / Missing Features:

- **Multi-State Machines**: Importing other state machines is not yet supported.
- **Domains**: The C/C++ domain and others are not yet available, so import statements will not work.
- **Subdiagrams**: Creating subdiagrams is not supported.
- **Import & Export**: Exporting or importing existing statecharts is not possible. However, models from the web version with an `.scm` file extension can be used.
- **SCTUnit**: Creating tests with SCTUnit is not supported.
