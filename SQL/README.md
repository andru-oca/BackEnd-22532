# SQL
---


Bases de datos Relacionales.\
---

Relacion entre tablas 
Los principales usos es de gestion de usuarios, de registros y de optimización de la información de cualquier modelo de negocio

Que es una base de datos RELACIONAL y NoSQL


Modelo entidad Relacion

# DER
---
### DER creado con excalidraw de un registro de padres
- [registro_padres DER](https://excalidraw.com/#json=WiL6iyOHNwNUrViUIgEoM,YDzDurlYuSUSCG0z4Mfg1g)


Links para generar DER's
- [DRAW io](https://app.diagrams.net/)
- [Excalidraw](https://excalidraw.com/)
---

# CARDINALIDAD
---
- Relaciones de 1-1
- Relaciones de 1-*
- Relaciones de *-*
---

# TIPOS DE DATOS
---
- VARCHAR
- DECIMAL
- DATE
- BOOLEAN

# PRIMARY KEY | FOREIGN KEY 
---

- PRIMARY KEY :\
IDENTIFICACION UNICA DE REGISTRO 
- FOREIGN KEY :\
ES LA CLAVE QUE VIAJA DE UNA TABLA A LA OTRA PARA RELACIONARSE Y GENERAR UN VINCULO CON EL REGISTRO DE LA TABLA PADRE

Instalación del motor de base de datos, en este caso vamos a usar MySQL : 
https://dev.mysql.com/downloads/mysql/
Siempre recordar el usuario root y su password


Conexion y creacion de usuario con tipo de conexión vieja.

Extensiones a usar: 
SQL tools | MySQL 

Ingresar al motor de bases de datos: 

creacion de usuarios :\
_CREATE USER 'admin'@'%' IDENTIFIED WITH mysql_native_password BY 'admin';_

Dar permisos y sus privilegios respectivos\
_GRANT ALL PRIVILEGES ON *.* TO 'admin'@'%' ;_

Otorgarlos y ejecutarlos:\
_FLUSH PRIVILEGES;_

---
Formas de insertar una base de datos
Base de datos para pruebas
Sakila : 
Buscar formas distintas de importar esa db (recomendacion de consola)



# CONCEPTOS BASICOS DE CREACION INSERCION Y ELIMINACION DE DATOS


### LINKS DE INTERES
---

- [sakila data info](https://github.com/jOOQ/sakila)
  - Primer paso mysql-sakila-schema.sql
  - Segundo paso mysql-sakila-insert-data.sql
  
 - [SQL](https://www.youtube.com/watch?v=uUdKAYl-F7g)
 - [SQL init](https://www.youtube.com/watch?v=e8gaffa3Ca8)
