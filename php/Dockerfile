FROM php:8.1-fpm 
RUN apt-get update && apt-get install -y \
    git \
    zip \
    unzip

RUN apt-get update && \
    apt-get install -y \
    libicu-dev \
    && docker-php-ext-configure intl \
    && docker-php-ext-install intl
