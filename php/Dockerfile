 FROM php:8.2-apache
 # Instala y habilita la extensión mysqli
 RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
 COPY . /var/www/html/concesionario
 RUN chown -R www-data:www-data /var/www/html/concesionario
