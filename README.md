# Framie

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

#### WARNING! Do not use this application. It was created for the purpose of training!

## Structure

```
.github/
build/
docs/
src/
tests/
vendor/
```


#### WARNING! Do not use this application. It was created for the purpose of training!

## Install

Via Composer

``` bash
$ composer require nastybits/framie
```

#### WARNING! Do not use this application. It was created for the purpose of training!

## Usage

``` php
$app = new nastybits\framie\base\Framie::instance($config);
$app->run();
```

#### WARNING! Do not use this application. It was created for the purpose of training!

## Change log

Please see [CHANGELOG](.github/CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) and [CODE_OF_CONDUCT](.github/CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email screamie@yandex.ru instead of using the issue tracker.

## Credits

- [Podosenov Dmitry][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/nastybits/framie.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/nastybits/framie/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/nastybits/framie.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/nastybits/framie.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/nastybits/framie.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/nastybits/framie
[link-travis]: https://travis-ci.org/nastybits/framie
[link-scrutinizer]: https://scrutinizer-ci.com/g/nastybits/framie/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/nastybits/framie
[link-downloads]: https://packagist.org/packages/nastybits/framie
[link-author]: https://github.com/nastybits
[link-contributors]: ../../contributors
