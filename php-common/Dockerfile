FROM php:7.2.1-apache-stretch

RUN apt-get update \
    && apt-get install -y zlib1g-dev \
    && docker-php-ext-install pdo_mysql mysqli mbstring \
    && apt-get install -y vim
