# <p align="center">Meilisearch Breeze / Magento 2 (Adobe Commerce)</p>

This module provides Breeze compatibility for the main [Meilisearch for Magento 2](https://github.com/walkwizus/magento2-module-meilisearch) module.  
It enables native integration with the [Breeze](https://breezefront.com/) frontend by adapting components and dependency management.

## Prerequisites

* Magento >= 2.4.4
* Meilisearch >= v1.9.0
* PHP >= 8.1
* Breeze >= 2.22.3

Magento 2 module install

```
composer require walkwizus/magento2-module-meilisearch-breeze
bin/magento module:enable Walkwizus_MeilisearchBreeze
bin/magento setup:upgrade
```
