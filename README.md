[![Latest Stable Version](https://img.shields.io/packagist/v/friends-of-phpspec/phpspec-expect.svg)](https://packagist.org/packages/friends-of-phpspec/phpspec-expect)
[![Total Downloads](https://img.shields.io/packagist/dt/friends-of-phpspec/phpspec-expect.svg)](https://packagist.org/packages/friends-of-phpspec/phpspec-expect)
[![Continuous Integration](https://github.com/friends-of-phpspec/phpspec-expect/actions/workflows/ci.yml/badge.svg)](https://github.com/friends-of-phpspec/phpspec-expect/actions/workflows/ci.yml)
[![License](https://img.shields.io/packagist/l/friends-of-phpspec/phpspec-expect.svg)](https://packagist.org/packages/friends-of-phpspec/phpspec-expect)

# phpspec-expect

## Install

Install this package as a development dependency in your project:

    $ composer require --dev friends-of-phpspec/phpspec-expect

## Usage

Inside some example:

```php
expect(file_exists('dummy.txt'))->toBe(true);
```

## Compatibility

| phpspec-expect | PHP     | phpspec          |
|----------------|---------|------------------|
| 3.0.x          | `>=7.0` | `^4.0`           |
| 3.1.x          | `^7.1`  | `^5.0 \|\| ^6.0` |
| 4.0.x          | `>=7.3` | `^6.0 \|\| ^7.0` |
| 4.1.x          | `>=8.1` | `^7.0 \|\| ^8.0` |

## Authors

Copyright (c) 2017-2020 BossaConsulting (https://github.com/BossaConsulting/phpspec2-expect).

## License

Licensed under [MIT License](LICENSE).
