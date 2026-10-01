# Yii2 PHP Docker Image
# About
This image is based on the official image [yiisoftware/yii2-php:8.5-fpm](https://github.com/yiisoft/yii2-docker#yii2-php-docker-image).

Certain adjustments have been made for use in custom projects. `php.ini-production` has been set as the `php.ini` file, and specific Linux packages—`unzip` and `locales`—have been installed. 
Additionally, the `ru_RU.UTF-8` Russian locale has been installed.
