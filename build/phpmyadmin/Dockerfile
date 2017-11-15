FROM php:apache

EXPOSE 80

COPY ./phpmyadmin /var/www/html

RUN docker-php-ext-install pdo pdo_mysql mysqli