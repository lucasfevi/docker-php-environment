FROM php:5.6-apache
MAINTAINER Lucas Vieira <newlucasfevi@gmail.com>

# Copy php.ini
COPY ./php.ini /usr/local/etc/php/

# Workaround to enable apache to write on folders
RUN usermod -u 1000 www-data