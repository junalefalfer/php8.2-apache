# Lexi Fact Backend

## Descripción

PHP8.2-apache es una imagen base actualizada y listo para correr proyectos de laravel.

### Características Principales

- **Actualizacion**: apt-get update
- **Instalaciond de librerias**: apt-get install -y libzip-dev zip unzip git libpng-dev libonig-dev libxml2-dev
- **Mysql Client y SOAP**: docker-php-ext-install pdo_mysql mbstring zip exif pcntl bcmath gd zip soap
- **Habilitacion de SOAP**: docker-php-ext-enable soap
- **Seguridad**: Autenticación JWT con middleware específico por tenant

## Requisitos del Sistema

- **PHP**: >= 8.2
