FROM php:8.2-apache

# Copia os arquivos do seu projeto para dentro do container
COPY . /var/www/html/

# Dá permissão de leitura e escrita aos arquivos
RUN chown -R www-data:www-data /var/www/html

# Ativa o módulo mysqli (para MySQL)
RUN docker-php-ext-install mysqli
