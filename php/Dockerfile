FROM php:7.2-apache-stretch
RUN apt-get update \
&& apt-get install -y libpq-dev libicu-dev zip unzip git zlib1g-dev vim \
&& docker-php-ext-install pdo_mysql pdo_pgsql mysqli mbstring zip intl
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
