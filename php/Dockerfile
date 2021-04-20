FROM php:7.4-fpm-alpine

RUN mkdir -p /var/www/html

WORKDIR /var/www/html

RUN docker-php-ext-install mysqli pdo pdo_mysql
