# Manage approval processes in your filament application

[![Latest Version on Packagist](https://img.shields.io/packagist/v/eightynine/filament-approvals.svg?style=flat-square)](https://packagist.org/packages/eightynine/filament-approvals)
[![Total Downloads](https://img.shields.io/packagist/dt/eightynine/filament-approvals.svg?style=flat-square)](https://packagist.org/packages/eightynine/filament-approvals)


This package allows you to implement approval flows in your Laravel Filament application.

Some processes in your application require to be approved by multiple people before they process can be completed. For example, 

_This package brings the ringlesoft/laravel-process-approval functionalities to filament. You can use all the ringlesoft/laravel-process-approval features in your laravel project_

## Quick understanding the package

### Approval flow

An approval flow is the step by step

## Installation

You can install the package via composer:

```bash
composer require eightynine/filament-approvals
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="filament-approvals-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="filament-approvals-config"
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="filament-approvals-views"
```

This is the contents of the published config file:

```php
return [
];
```

## Usage

```php
$approval = new EightyNine\Approval();
echo $approval->echoPhrase('Hello, EightyNine!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Eighty Nine](https://github.com/eighty9nine)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
