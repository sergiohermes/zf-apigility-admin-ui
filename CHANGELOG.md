# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 1.3.0 - TBD

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [#93](https://github.com/zfcampus/zf-apigility-admin-ui/pull/93) updates how
  controller names are sent to the admin API, providing the fully qualified
  class name. This update allows the UI to properly work with modules that use a
  PSR-4 directory structure.
- [#97](https://github.com/zfcampus/zf-apigility-admin-ui/pull/97) updates all
  API calls that pass the module name to normalize the module name using
  `encodeURIComponent()`; this allows using sub-namespaces in the backend code.

## 1.2.4 - 2016-07-27

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [#54](https://github.com/zfcampus/zf-apigility-admin-ui/pull/54) fixes display
  of field names generated from Doctrine entities, and also updates it to allow
  display and usage of underscore-separated names.
- [#85](https://github.com/zfcampus/zf-apigility-admin-ui/pull/85) adds
  additional information to error messages when unable to create a new service
  for reasons other than conflicts.
- [#91](https://github.com/zfcampus/zf-apigility-admin-ui/pull/91) fixes the
  templates for adding and editing validators and filters with boolean switches
  such that they now work properly.
- [#99](https://github.com/zfcampus/zf-apigility-admin-ui/pull/99) updates the
  template to make the copyright date in the footer dynamic.