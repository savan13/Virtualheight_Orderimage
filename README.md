# Mage2 Module Virtualheight Orderimage

    ``virtualheight/module-orderimage``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities
 Display Product images on Sales Order View details page at backend

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Virtualheight`
 - Enable the module by running `php bin/magento module:enable Virtualheight_Orderimage`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require virtualheight/module-orderimage`
 - enable the module by running `php bin/magento module:enable Virtualheight_Orderimage`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration




## Specifications




## Attributes


## Output
![Screenshot](https://user-images.githubusercontent.com/38579373/123244940-feb6ab80-d501-11eb-9ea4-0cfc6af0a9af.png)
