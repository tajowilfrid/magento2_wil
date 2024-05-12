FROM markoshust/magento-php:8.3-fpm-2

USER root

RUN apt-get update

RUN docker-php-ext-install calendar

RUN apt-get install nano


USER app

