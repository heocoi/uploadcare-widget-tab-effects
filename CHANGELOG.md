# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]



[Unreleased]: https://github.com/uploadcare/uploadcare-widget-tab-effects/compare/v1.2.1...HEAD

## [1.2.1] - 2018-06-28

### Fixed

* Not working crop in Safari, see [#24][github-pr-24].

[1.2.1]: https://github.com/uploadcare/uploadcare-widget-tab-effects/compare/v1.2.0...v1.2.1
[github-pr-24]: https://github.com/uploadcare/uploadcare-widget/pull/24

## 1.2.0 - 2018-05-23

### Added

* Support for new widget configuration options:
  [`previewProxy`](https://uploadcare.com/docs/uploads/widget/config/#option-preview-proxy),
  [`previewUrlCallback`](https://uploadcare.com/docs/uploads/widget/config/#option-preview-url-callback).
  Learn more [here](https://uploadcare.com/docs/uploads/widget/secure_urls/).
* French (`fr`) locale thanks to [@gpenverne](https://github.com/gpenverne).

### Changed

* Updated README:
  * references,
  * added Feedback section,
  * removed Contributors section.

### Fixed

* Autorotate for image preview, [#21][github-pr-21].

[github-pr-21]: https://github.com/uploadcare/uploadcare-widget-tab-effects/pull/21

## 1.1.0 - 2018-04-20

### Fixed

* Global setting `UPLOADCARE_EFFECTS` works now.
* Fixed ignoring of the `crop` preset in multiple mode.
* Crop is applied automatically if
  the `crop` setting has presets, e.g. `1:1`, and hasn't `free`.
* Show an image without all effects in the crop mode.

### Added

* New effect `invert`.
* New option `all` for effects settings.

## 1.0.3 - 2017-08-23

### Fixed

* Fix links to uploadcare site in README.

## 1.0.2 - 2017-08-21

### Added

* Uploadcare logo into README.

## 1.0.1 - 2017-08-21

Initial public release for npm.

### Fixed

* Fix info about version in README.

### Added

* README section about install with npm.
* README section about output value.

## 1.0.0 - 2017-08-21

Initial public release.

### Added

* The `uploadcareTabEffects` function as default export.
* README with info about requirements, install, usage, etc.
