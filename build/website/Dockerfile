FROM php:apache

EXPOSE 80

RUN a2enmod rewrite
#RUN a2enmod ssl

RUN docker-php-ext-install pdo pdo_mysql mysqli