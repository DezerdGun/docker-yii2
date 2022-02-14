FROM php:7.4-fpm
RUN docker-php-ext-install pdo pdo_mysql pcntl

RUN apt-get update

RUN apt-get install -y apt-utils unzip libzip-dev libpq-dev libjpeg-dev libpng-dev libfreetype6-dev libmemcached-dev
RUN apt-get install -y libicu-dev iproute2 iputils-ping git
RUN apt-get install -y libmagickwand-dev

RUN docker-php-ext-configure gd --with-freetype
RUN docker-php-ext-install zip pdo_pgsql pdo_mysql gd intl


COPY --from=composer:latest /usr/bin/composer /usr/bin/composer




