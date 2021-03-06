# Change Log

All notable changes to the "vscode-puppet" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## Unreleased
## 0.7.2 - 2017-11-01

- (GH-165) Broken readme link
- (GH-88)  Rework Node Graph Preview to use local svg
- (GH-154) Use hosted JSON schema files
- (GH-169) Fix bug in sytanx highlighting
- (GH-167) Add PDK New Task command
- (GH-156) Document restarting Puppet extension command
- (GH-177) Remove detection of Puppet VERSION file
- (GH-175) Fix 'could not find valid version of Puppet'

## 0.7.1 - 2017-09-29

- (GH-157) Puppet Resource command hidden

## 0.7.0 - 2017-09-22

- (GH-115) Add Puppet Development Kit (PDK) integration
- (GH-136) Create a better UI experience while Puppet loads
- (GH-61)  Create a better experience when language client fails
- (GH-135) Fix incorrect logger when a client error occurs
- (GH-129) Honor inline puppet lint directives
- (GH-133) Fix issue with puppet 5.1.0
- (GH-122) Show upgrade message with changelog
- (GH-120) Allow custom Puppet agent installation directory
- (GH-126) Fix completion provider with Puppet 5.2.0
- (GH-110) Add extension analytics
- (GH-138) Set extension analytics to prod
- (GH-109) Randomize languageserver port
- (GH-111) Parse puppet-lint.rc in module directory

## 0.6.0 - 2017-08-08

- Fix packaging error where language server was not included

## 0.5.3 - 2017-08-08

- (GH-92) Added context menus for Puppet Resource and Nodegraph preview
- (GH-98) Improve language server function and type loading
- (GH-52) JSON validation and schema for metadata.json
- (GH-47) Fixes pending language server tests
- (GH-45) Fix runocop violations for language tcp server
- (GH-89) Document support for linux in readme
- (GH-64) Additional language server tests
- (GH-103) Extension now supports puppet-lint rc files
- (GH-99) Improved client README and Gallery page

## 0.4.6 - 2017-06-29

### Changed

- Updated links in README
- Added more information to package manifest
- Minor updates to README

## 0.4.5 - 2017-06-27

### Changed

- Updated badge link location in README

## 0.4.2 - 2017-06-27

### Changed

- Updated badge links to use proper extension id

## 0.4.0 - 2017-06-27

### Added

- A functional Language Server for the Puppet language
  - Real time puppet lint
  - Auto-complete and Hover support for many puppet language facets
  - Auto-complete and Hover support for facts
  - 'puppet resource' support
  - Preview node graph support
- Extension can load a local Language Server if Puppet Agent is present on Windows, Mac and Linux
- Tested on older Puppet versions (4.7 LTS series)
- Added testing on Travis and Appveyor

### Fixed

- Completion and Hover provider didn't load puppet modules
- Implemented textDocument/didClose notification
- Extension building is functional and automated in a gulpfile
- Fixed completion at file beginning on new lines and on keywords

## 0.0.3 - 2017-05-08

### Added

- Puppet Parser validate linter added

## 0.0.2 - 2017-05-04

### Added

- Puppet Resource and Puppet Module commands.

## 0.0.1 - 2017-04-10

### Added

- Initial release of the puppet extension.
