FROM php:7.0-fpm
MAINTAINER Lucas Vieira <newlucasfevi@gmail.com>

RUN apt-get update

# Install mcrypt
RUN apt-get install -y libmcrypt-dev
RUN docker-php-ext-install mcrypt

# Install XSL
RUN apt-get install -y libxslt-dev
RUN docker-php-ext-install xsl