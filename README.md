# Regiones, Provincias y Comunas de Chile.
SQL Con la información de las regiones, provincias y comunas de Chile según Decreto Exento Nº 817

Esta información fue publicada en el Diario Oficial el 26 de Marzo de 2010.

http://www.subdere.cl/documentacion/regiones-provincias-y-comunas-de-chile

 

|         |            |   |
| ------------- |:-------------:| -----:|
| Regiones     | 15|  |
| Provincias      | 54      |   |
| Comunas | 346      |   |

Los número de las Provincias y regiones corresponden a los que salen en el decreto.

## ¿ Cómo instalar ?

Simplemente agrega el código con phpmyadmin u otro gestor, o usando la línea de comandos de la siguiente manera :

    $ mysql -u MIUSUARIO -pMICLAVE MIBDD < sql/MysqlDUMP.sql

### Usando Composer
    composer require ctala/regiones-provincias-y-comunas-de-chile
