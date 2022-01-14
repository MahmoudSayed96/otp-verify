# OTP VERIFICATION

Drupal custom module for make otp verification using sms `Twilio` gateway.

## Installation

- download module files and set folder in path `web\modules\custom`.
- go to your project root and add to `composer.json` with code.

```php
    "repositories": [
    {
        "type": "path",
        "url": "web/modules/custom/otp_verify"
    }
],
```

- run this command to download dependencies.

```bash
composer require drupal/otp_verify
```

## CONFIGURATIONS

Please go to `/admin/config/otp-verify` to explore the configuration
options of the widget.

## UNINSTALL

Just uninstall the module since the connector.

## AUTHORS
- [@MahmoudSayed96](https://www.github.com/MahmoudSayed96)

__Mahmoud Sayed__       - Software Developer.
