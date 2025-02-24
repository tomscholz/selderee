# Changelog

## Version 0.8.1

* Bump `parseley` dependency to version 0.9.1 ([changelog](https://github.com/mxxii/parseley/blob/main/CHANGELOG.md)). Now all dependencies are TypeScript, dual CommonJS/ES module packages;
* Use `rollup-plugin-cleanup` to condition published files;
* Package is marked as free of side effects.

## Version 0.7.0

* Drop Node.js version 10 support. At least 12.22.x is required.

## Version 0.6.0

* Give priority to more common attribute values (Previously the first matching simple selector was taken instead);
* Repeated simple selectors should not affect the tree balance and should not produce extra tree nodes (But they affect the specificity).

## Version 0.5.0

Initial release.

Aiming at Node.js version 10 and up.
