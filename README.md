# WARNING!!!!!!

This has been forked from a specific commit because Respect Validator has dropped support for PHP 5.6, which means composer can no longer update and use the specific commit hash we're using on Respect Validator. We've changed the composer.json file locally.

# Respect\Validation

[![Build Status](https://img.shields.io/travis/Respect/Validation/master.svg?style=flat-square)](http://travis-ci.org/Respect/Validation)
[![Scrutinizer Code Quality](https://img.shields.io/scrutinizer/g/Respect/Validation/master.svg?style=flat-square)](https://scrutinizer-ci.com/g/Respect/Validation/?branch=master)
[![Code Coverage](https://img.shields.io/scrutinizer/coverage/g/Respect/Validation/master.svg?style=flat-square)](https://scrutinizer-ci.com/g/Respect/Validation/?branch=master)
[![Latest Stable Version](https://img.shields.io/packagist/v/respect/validation.svg?style=flat-square)](https://packagist.org/packages/respect/validation)
[![Total Downloads](https://img.shields.io/packagist/dt/respect/validation.svg?style=flat-square)](https://packagist.org/packages/respect/validation)
[![License](https://img.shields.io/packagist/l/respect/validation.svg?style=flat-square)](https://packagist.org/packages/respect/validation)

[The most awesome validation engine ever created for PHP.](http://bit.ly/1a1oeQv)

- Complex rules made simple: `v::numericVal()->positive()->between(1, 255)->validate($input)`.
- [Granularity control](docs/README.md#validation-methods) for advanced reporting.
- More than 100 (fully tested) validators.
- [A concrete API](docs/CONCRETE_API.md) for non fluent usage.
- Works on PHP 5.6+

## Table of contents

- [Contributing](CONTRIBUTING.md)
- [Feature Guide](docs/README.md)
- [Installation](docs/INSTALL.md)
- [License](LICENSE.md)
- [Validators](docs/VALIDATORS.md)
- [Changelog](CHANGELOG.md)
