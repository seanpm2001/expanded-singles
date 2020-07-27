# Changelog

## 1.1.3 - 2020-07-27

### Fixed
- Fix duplicate sidebar entry with "Redirect to Entry" set to true.

## 1.1.2 - 2020-04-16

### Fixed
- Fix logging error `Call to undefined method setFileLogging()`.

## 1.1.1 - 2020-04-15

### Changed
- File logging now checks if the overall Craft app uses file logging.
- Log files now only include `GET` and `POST` additional variables.

## 1.1.0 - 2020-04-01

### Changed
- Now requires Craft 3.4+.

## 1.0.11 - 2020-02-28

### Fixed
- Fix PHP error (again).
- Even more refactoring and cleanup JS/CSS.

## 1.0.10 - 2020-02-28

### Changed
- Refactor and cleanup JS/CSS.
- Add some debug statements.

### Fixed
- Fix PHP error.
- Fix minor styling caused by new overlay.

## 1.0.9 - 2020-02-11

### Changed
- Ensure URL to single redirect is correct on multisite. (thanks @andersaloof)

## 1.0.8 - 2020-02-05

### Added
- Add override notice for settings fields.

### Changed
- Change behaviour of “Redirect to Entry”, now using an overlay to retain normal element index filtering.

### Fixed
- Fix redactor singles not being site-aware.
- Be sure to include siteIds in single data for filtering.
- Ensure site filtering works with “Redirect to Entry” set.

## 1.0.7 - 2019-02-09

### Fixed
- Fix JS showing for non-CP requests.

## 1.0.6 - 2019-01-18

### Fixed
- Fixed non-admins not seeing expanded singles due to Craft 3.1 changes in permission filtering from id's to uid's.
- Now requires Craft 3.1+.

## 1.0.5 - 2018-10-24

### Fixed
- Better support multi-site enabled singles

## 1.0.4 - 2018-07-04

### Fixed
- Fix error caused by permissions to view singles

## 1.0.3 - 2018-02-20

### Fixed
- Fix error when the Redactor plugin isn’t installed

## 1.0.2 - 2018-02-12

### Added
- Added support for Redactor fields

### Fixed
- Update Craft CMS requirements
- Fix error when selecting an expanded single from a modal window

## 1.0.1 - 2017-12-07

### Changed
- Updated for Craft 3 RC1.

## 1.0.0 - 2017-10-18

### Added
- Craft 3 initial release.

## 0.2.5 - 2017-10-17

### Added
- Verbb marketing (new plugin icon, readme, etc).

### Changed
- Improve link hijacking.
- Allow functionality on element modal.

### Fixed
- Fix to work with multi-locales.

## 0.2.4 - 2017-01-23

### Changed
- Adding check to see if user can edit a particular single before adding that single to the list for display. Thanks to [@aberkie](https://github.com/aberkie).

## 0.2.3 - 2016-02-20

### Fixed
- Fixed issue when disabling a single, it would disappear from the sidebar in Entries Index [#2](https://github.com/engram-design/ExpandedSingles/issues/2).

## 0.2.2 - 2016-01-13

### Fixed
- Fixed issue with plugin release feed url.

## 0.2.1 - 2015-11-20

### Changed
- Removed plugin description (doesn't look great).

## 0.2.0 - 2015-11-20

### Changed
- Craft 2.5 compatibility, including plugin feed.
- Cleanup/organise code.

## 0.1.0 - 2015-06-06

- Initial commit
