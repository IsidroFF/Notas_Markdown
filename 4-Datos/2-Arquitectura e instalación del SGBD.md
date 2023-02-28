# 2.1 Estructura de memoria y procesos de la instancia
### Actividad 1 (22/Feb)
Link a la actividad completa: [Arquitectura de Oracle y SQL Server](https://docs.google.com/document/d/16FGkJepcyqon5WKNmG7m_ZwQmqQEzV6LGJjZ7cVPu6U/edit#)


### Actividad 2 (23/Feb)
Desventajas de FILE-PER-TABLE TABLESPACE en MySQL
- La gestión de cada archivo diferente es muy difícil y requiere mucho tiempo.
- Cada archivo diferente tiene espacio sin usar, por lo que necesitamos realizar OPTIMIZE TABLE en cada archivo individual.
- Mysqld tiene que abrir un controlador de archivos por tabla, lo que puede reducir el rendimiento de MySQL Server.
- Para cada acción de cada grupo de búfer de archivo se escanea, lo que reduce el rendimiento de MySQL Server.
Fuente: [MySQL: The Truth about InnoDB File Per Table Tablespaces](https://www.dbrnd.com/2016/09/mysql-the-truth-about-innodb-file-per-table-tablespaces/)

**Instancia:** Son procesos dentro del SGDB, comunmente se tienen multiples instancias que fungen como servidor...?
# 2.2 Estructura física de la base de datos
# 2.3 Requerimientos para instalación
# 2.4 Instalación del SGBD en modo transaccional
# 2.5 Variables de Ambiente y archivos importantes para instalación
# 2.6 Procedimiento general de instalación
# 2.7 Procedimiento para configuración de un SGBD
# 2.8 Comandos generales de alta y baja del SGBD