# SMS Aero
Drupal 7 module allow use SMS Aero gateways in your Drupal projects.

Wrapped SMS Aero PHP class (http://smsaero.ru/api/class-php) to Drupal 7 module.

## Requirements:
1. cURL

## Using:

```php

$client = sms_aero_get_client();
$client->send($to, $text);

```

## Documentation:
See other API methods on the page: http://smsaero.ru/api/description
