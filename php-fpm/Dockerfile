FROM php:7.3.0-fpm
RUN apt update &&  apt-get install -y \
libzip-dev && docker-php-ext-install pdo_mysql && docker-php-ext-install zip \
&& pecl install redis-4.2.0 && docker-php-ext-enable redis