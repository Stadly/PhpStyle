# PhpStyle

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]

Coding standard for Stadly PHP projects.

## Install

Install package [`stadly/php-style`](https://packagist.org/packages/stadly/php-style) with [Composer](https://getcomposer.org/):

``` bash
composer require --dev stadly/php-style
```

## Usage

Run [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) with this standard:

``` bash
vendor/bin/phpcs src --standard=vendor/stadly/php-style/StadlyCodingStandard -p
```

For further usage options, see the [PHP_CodeSniffer documentation](https://github.com/squizlabs/PHP_CodeSniffer/wiki).

## Security

If you discover any security related issues, please email magnar@myrtveit.com instead of using the issue tracker.

## Credits

- [Magnar Ovedal Myrtveit][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/stadly/php-style.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/stadly/php-style.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/stadly/php-style
[link-downloads]: https://packagist.org/packages/stadly/php-style
[link-author]: https://github.com/Stadly
[link-contributors]: ../../contributors
