# LaraZkteo
LaraZkteo is Zkteo  Biometrics Technology Integration with Laravel

[![Latest Stable Version](https://poser.pugx.org/mdsami/larapaytm/v/stable)](https://packagist.org/packages/mdsami/larapaytm)
[![Total Downloads](https://poser.pugx.org/mdsami/larapaytm/downloads)](https://packagist.org/packages/mdsami/larapaytm)
[![License](https://poser.pugx.org/mdsami/larapaytm/license)](https://packagist.org/packages/mdsami/larapaytm)



For Laravel 5.6 and above

## Introduction
Integrate LaraZkteo  in your laravel application easily with this package. This package uses Zkteo's php SDK.

## License
Laravel ZKteo  open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

## Getting Started
To get started add the following package to your `composer.json` file using this command.

    composer require mdsami/LaraZkteo

## Configuring
**Note: For Laravel 5.5 and above auto-discovery takes care of below configuration.**

When composer installs Laravel ZKteo  library successfully, register the `mdsami\LaraPLaraZkteo\LaraZkteoServiceProvider` in your `config/app.php` configuration file.

```php
'providers' => [
    // Other service providers...
    mdsami\LaraZkteo\LaraZkteoServiceProvider::class,
],
```
Also, add the `LaraZkteo` facade to the `aliases` array in your `app` configuration file:

```php
'aliases' => [
    // Other aliases
    'LaraZkteo' => mdsami\LaraZkteo\Facades\LaraZkteo::class,
],
```
#### Add the paytm credentials to the `.env` file