# SQL
---


Bases de datos Relacionales
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


## Conexion y creacion de usuario con tipo de conexión vieja.
--- 

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


---
# MUY IMPORTANTE ES SABER DONDE HAN INSTALADO EL SERVIDOR, POR LO GENERAL EL SERVIDOR EN WINDOWS SE TERMINA GUARDANDO EN LA CARPETA QUE SE ENCUENTRA EN PROGRAM FILES\
_C:\Program Files\MySQL\MySQL Server 8.0\bin>_
---
# BACKUP RAPIDO POR CONSOLA
---
* Parados en la ruta donde se encuentra el archivo mysqldump:\
  - _C:\Program Files\MySQL\MySQL Server 8.0\bin>mysqldump -u root -p <nombre_de_la_base_de_datos> > <nombre_del_bk_con_la_ruta.sql>_


# RESTORE RAPIDO POR CONSOLA
*IDEM anterior pero con la flechita al revés
  - Previo a esto deben crear una base con el nombre que quieran crear.
  - _C:\Program Files\MySQL\MySQL Server 8.0\bin>mysqldump -u root -p <nombre_de_la_base_de_datos> < <nombre_del_bk_con_la_ruta.sql>
---

---

# CONCEPTOS BASICOS DE CREACION INSERCION Y ELIMINACION DE DATOS


### LINKS DE INTERES
---

- [sakila data info](https://github.com/jOOQ/sakila)
  - Primer paso mysql-sakila-schema.sql
  - Segundo paso mysql-sakila-insert-data.sql
  
 - [SQL](https://www.youtube.com/watch?v=uUdKAYl-F7g)
 - [SQL init](https://www.youtube.com/watch?v=e8gaffa3Ca8)
