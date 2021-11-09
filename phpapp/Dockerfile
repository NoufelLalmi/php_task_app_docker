FROM php:8-apache
#RUN apt-get update
RUN apt-get update
RUN docker-php-ext-install mysqli pdo pdo_mysql
RUN docker-php-ext-enable mysqli
#RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
EXPOSE 80