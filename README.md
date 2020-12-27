# Tr Tax Number Verification Class

<p align="center">
<a href="https://packagist.org/packages/X-Adam/tr-tax-number-verification" rel="nofollow"><img src="https://img.shields.io/packagist/v/X-Adam/tr-tax-number-verification" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/X-Adam/tr-tax-number-verification" rel="nofollow"><img src="https://img.shields.io/packagist/dt/X-Adam/tr-tax-number-verification" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/X-Adam/tr-tax-number-verification" rel="nofollow"><img src="https://poser.pugx.org/X-Adam/tr-tax-number-verification/dependents.svg" alt="Dependents"></a>
<a href="https://packagist.org/packages/X-Adam/tr-tax-number-verification" rel="nofollow"><img src="https://img.shields.io/packagist/l/X-Adam/tr-tax-number-verification" alt="License"></a>
</p>

<p align="center">
<a href="https://scrutinizer-ci.com/g/X-Adam/tr-tax-number-verification/build-status/master" rel="nofollow"><img src="https://scrutinizer-ci.com/g/X-Adam/tr-tax-number-verification/badges/quality-score.png?b=master" title="Scrutinizer Code Quality"></a>
<a href="https://styleci.io/repos/324771706" rel="nofollow"><img src="https://styleci.io/repos/324771706/shield?branch=master" alt="StyleCI"></a>
</p>

## Introduction

Turkey tax number verification class.

## Requirements

1. PHP >=7.4
2. PHP Curl extension have to be loaded.

Other than that, this library has no requirements.

## Install

```bash
$ composer require x-adam/tr-tax-number-verification:"~4"
```

## Example Usage

```php
include "./vendor/autoload.php";

$result = XAdam\TrTaxNumberVerification::verify(1, '3331970048', '035267');
var_dump($result);    # Result: bool(false)
```

## License

This package is open source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
