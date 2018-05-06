# Laravel Chart Helper

Helpers to integrate Highcharts with Laravel

## Requirements

Laravel 5.6+


## Installation

You can install the package through [Composer](http://getcomposer.org/)
with the following command

```bash
composer require pawprintdigital/laravel-charts
```

### Service Provider

The service provider should register with Laravel automatically
through Laravel 5.6's package discovery feature.

If this doesn't work, you can  manually register the service
provider by  adding the following line to the `providers`
array in your `config/app.php` file.

```php
PawprintDigital\LaravelCharts\LaravelChartsServiceProvider::class
```
