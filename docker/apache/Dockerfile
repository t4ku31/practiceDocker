FROM php:7.0-apache

LABEL desc="php-sandbox apache"

COPY ./docker-php.conf /etc/apache2/conf-enabled/docker-php.conf

RUN docker-php-ext-install mysqli
