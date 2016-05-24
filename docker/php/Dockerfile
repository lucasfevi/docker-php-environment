FROM php:7.0-fpm
MAINTAINER Lucas Vieira <newlucasfevi@gmail.com>

RUN apt-get update

# Install XSL
RUN apt-get install -y libxslt-dev
RUN docker-php-ext-install xsl