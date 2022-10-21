# SQL
---


Bases de datos Relacionales.\
---

Relacion entre tablas 
Los principales usos es de gestion de usuarios, de registros y de optimización de la información de cualquier modelo de negocio

Que es una base de datos RELACIONAL y NoSQL


Modelo entidad Relacion

Instalación del motor de base de datos, en este caso vamos a usar MySQL : 
https://dev.mysql.com/downloads/mysql/
Siempre recordar el usuario root y su password


Conexion y creacion de usuario con tipo de conexión vieja.

Extensiones a usar: 
SQL tools | MySQL 

Ingresar al motor de bases de datos: 

creacion de usuarios : 
CREATE USER 'admin'@'%' IDENTIFIED WITH mysql_native_password BY 'admin';

Dar permisos y sus privilegios respectivos
GRANT ALL PRIVILEGES ON *.* TO 'admin'@'%' ;

Otorgarlos y ejecutarlos:
FLUSH PRIVILEGES;
