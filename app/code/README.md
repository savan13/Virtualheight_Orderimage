# Module Virtualheight Orderimage

    ``virtualheight/module-orderimage``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)
 - [Output](#markdown-header-output)


## Main Functionalities
 Display Product images on Sales Order View details page at backend in magento 2

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
![image](https://user-images.githubusercontent.com/38579373/123396433-efe1fe80-d5be-11eb-983e-63e4f62827c9.png)

