# bitfinex-v1
## Bitfinex API wrapper V1
I get from somewhere (can't remember where, sorry) this API and make few changes for my own need.

## Install
```
composer require bedri/bitfinex-v1
```

## Usage
```php
<?php

// Autoload files using the Composer autoloader.
require_once __DIR__ . '/../../vendor/autoload.php';

use Bitfinex\BitfinexV1;

$apiKey     = 'x';
$apiSecret  = 'y';

$bitfinex = new BitfinexV1($apiKey, $apiSecret);

print_r($bitfinex->platform_status());
```
