# tenpal
Drupal 10 sandbox project

## Local requirements

* [Composer](https://getcomposer.org/doc/00-intro.md)
* [Lando](https://docs.lando.dev/getting-started/installation.html)
  * Lando should install docker and docker-desktop as dependencies

## Local installation

```
git clone git@github.com:philippemouchel/tenpal.git
cd tenpal
composer install
cp build/local/settings.php web/sites/default/settings.php
cp build/local/settings.local.php web/sites/default/settings.local.php
lando start
```
