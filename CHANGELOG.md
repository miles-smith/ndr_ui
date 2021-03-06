## [Unreleased]
*no unreleased changes*

## 2.0.2 / 2019-01-18
### Fixed
* Ensure that RubyGems doesn't re-write symlinked asset wrongly

## 2.0.1 / 2019-01-18
### Fixed
* Repacked gem without tests

## 2.0.0 / 2019-01-17
### Changed
* for input fields with `input-addons`, remove background and border when the form is read-only. (#24)
* `delete_link` now adds a `data-confirm` attribute by default (#25)
* `{details,edit,delete}_link` integrate with authorisation, if possible (#26)

### Added
* `form_with` can use `NdrUi::BootstrapBuilder` as builder, also added `bootstrap_form_with` helper method as shortcut (#32)
* Added `bootstrap_icon_spinner` helper methods
* Add `inline_controls_for` button toolbar helper (#27)

### Fixed
* Support Ruby 2.6. Ruby 2.4 / Rails 5.1 is now the minimum requirement.

## 1.12.2 / 2018-06-22
### Fixed
* Address issue with datepicker SCSS (#22)

## 1.12.1 / 2018-05-01
### Fixed
* Correct issue with inline errors

## 1.12.0 / 2018-04-27
### Added
* Add support for Rails 5.1 / 5.2
* Added `bootstrap_modal_{dialog,header,body,footer}_tag` helper methods
* Added readonly ``bootstrap_modal_box`` button option

### Fixed
* `inline_errors` shouldn't break with basic objects
* Add fix for inline errors issue
* try to fix some I18n issues
* fix tooltips tests that had previously been spuriously passing
* Ensure `assert_select` is being used correctly. Resolves #18.
* fix SASS precompilation when using datepicker
* labels should not contain the 'for' HTML attribute when readonly (#16)
* Fix to the label `tooltip: false`. Resolves #15
