# amezmo-drupal-integrations

Add this project to any Drupal distribution based on drupal/core-composer-scaffold to enable it for use on Amezmo.

This project provides a custom settings file and a few other small changes necessary to run Drupal on Amezmo.

## Enabling this project

This project must be enabled in the top-level composer.json file, or it will be ignored and will not perform any of its functions.
```
{
    ...
    "require": {
        "sdubois/amezmo-drupal-integrations": "^9"
    },
    ...
    "extra": {
        "drupal-scaffold": {
            "allowed-packages": [
                "sdubois/amezmo-drupal-integrations"
            ]
        }
    }
}
```

## Credit

This repository is based on the pantheon-systems/drupal-integrations project. Thanks to everyone involved!

## Versions

Use version "^8" for Drupal 8, and version "^9" for Drupal 9.