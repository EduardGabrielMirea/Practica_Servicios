FROM php:7-apache

# Activamos el módulo LDAP de Apache ejecutando el siguiente comando
RUN a2enmod authnz_ldap

# Creamos el directorio test como en la práctica anterior
RUN mkdir -p /var/www/html

#Copiamos los ficheros como los de la práctica anterior
COPY index.html /var/www/html/index.html

COPY 000-default.conf /etc/apache2/sites-enabled/000-default.conf