FROM php:7.0-fpm
MAINTAINER Lucas Vieira <newlucasfevi@gmail.com>

RUN apt-get update

# Install opcache
RUN docker-php-ext-install opcache

# Install APCu
RUN pecl install apcu-5.1.4
RUN echo extension=apcu.so > /usr/local/etc/php/conf.d/apcu.ini

# Install mcrypt
RUN apt-get install -y libmcrypt-dev
RUN docker-php-ext-install mcrypt

# Install XSL
RUN apt-get install -y libxslt-dev
RUN docker-php-ext-install xsl