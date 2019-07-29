FROM php:7.3-fpm
RUN apt -yqq update
RUN apt -yqq install libxml2-dev
RUN docker-php-ext-install pdo_mysql
RUN docker-php-ext-install xml
RUN docker-php-ext-install mysqli
RUN docker-php-ext-enable mysqli