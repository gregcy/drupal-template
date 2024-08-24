# Drupal Starter Template

This is a starter template for Drupal 10 projects. It includes a basic setup for a Drupal 10 site along with config split setup with a development profile that includes all tools required for local development.

It also includes both Lando and DDEV configurations to create the local development stack with a single command.

## Requirements

To use either Lando or DDEV, you need to have them setup on your local machine. You can find the installation instructions for both tools below:

- [Lando Installation](https://docs.lando.dev/basics/installation.html)
- [DDEV Installation](https://ddev.readthedocs.io/en/stable/#installation)

## Lando

Lando is configured to use the following:

- PHP 8.3
- MySQL 8.0
- Nginx 1.21
- Composer 2.7

To start the Lando environment, run the following command:

```
lando start
```
You can enable or disable Xdebug by running the following commands after you start the Lando environment:

```
lando xdebug-on
lando xdebug-off
```
## DDEV
todo

## What is Included

### Core and Contrib modules:
- [Drupal 10](https://www.drupal.org/project/drupal/releases)
- [Drush 13](https://www.drush.org/13.x/)
- [Config Split](https://www.drupal.org/project/config_split)

### Development modules (require-dev)
- [Devel](https://www.drupal.org/project/devel)
- [Devel Kint Extras](https://www.drupal.org/project/devel_kint_extras)
- [Drupal Coder](https://www.drupal.org/project/coder)
- [Drupal Examples](https://www.drupal.org/project/examples)
- [Project Browser](https://www.drupal.org/project/project_browser)
- [Stage File Proxy](https://www.drupal.org/project/stage_file_proxy)
- [Upgrade Status](https://www.drupal.org/project/upgrade_status)
- [Webprofiler](https://www.drupal.org/project/webprofiler)

### Composer Patches
The [cweagnas/composer-patches](https://github.com/cweagans/composer-patches) is included to allow management of patches for both Drupal core and contributed modules using the composer.json file.

### Libraries Installation via Composer
