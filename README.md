# Number to words
Laravel package for the translation of numbers to words

## Install
Install package with composer
```
composer require aizhar777/numbers-to-words
```
Publish config
```
php artisan vendor:publish --provider="aizhar777\numbers-to-words\NumToWordServiceProvider" --tag="config"
```

#### Add Provider
```php
Aizhar777\NumToWord\NumToWordServiceProvider::class,
```
#### Add Facade
```php
'Cell' => Aizhar777\NumToWord\Facades\NumberToWordsFacade::class,
```