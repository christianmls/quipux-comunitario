# quipux-comunitario

Quipux es un sistema basado en el Sistema de Gestión Documental Orfeo en el año 2007, ha sido modificado y adaptado a las necesidades de Instituciones Públicas para la gestión Documental.
La versión comunitaria ha sido adaptado para uso de GADS, Instituciones, Organizaciones, Companías y Empresas.
Licenciado como software Libre, GNU/GPL para la distribución libre, gratuita además de compartir los conocimientos y modificaciones.

# Requerimientos
* Centos, Ubuntu
* Apache
* PostgreSQL
* Git
* PHP 7.4

# Paquetes
* php
* php-soap
* php-pdo
* php-pgsql
* html2ps

# Configuraciones adicionales

Remplace por su dominio o ip local


* cp example.config.php config.php
* cp html_a_pdf/example.config.php html_a_pdf/config.php
* cp html_a_pdf/example.html_a_pdf.wsdl html_a_pdf/html_a_pdf.wsdl

# Configuración de base de datos

Crear dos bases de datos (transacional y documental), descargue los scripts desde:

https://minka.gob.ec/quipux-comunitario/scripts_data


# Requerimientos de Hardware
* Almacenamiento de base de datos anual.

* Servidores de Base de datos

| Tipo | Disco | Memoria GB | Procesador Ghz |
| ------ | ------ | ------ | ------ |
| Transaccional | 30 | 6 | 3.4 | 
| Documental | 8GB | 6 | 3.4 | 

* Servidor Web
Disco 30Gb
Memoria 6Gb
Procesador 3.4 Ghz

