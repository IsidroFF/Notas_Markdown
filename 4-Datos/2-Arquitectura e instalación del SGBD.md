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

**Capas logicas de proceos**
1. Query processing
2. Transaction managment
3. Reco
4. Storage managment

**Capa logica de procesamiento**
1. Capa de interfaz -> *Procesamiento de consutas*
2. Capa de aplicacion -> *Gestores de transacciones y de recuperacion*
3. Capa fisica de datos -> *Gestor de almacenamiento*

**API's**
Permiten conectarnos con las bases de datos y realizar el procesamiento de datos.
Pull de concexciones: Gestiona el orden de conexiones con la base de datos

**Arquitectua de oracle**
Los procesos de cliente, servidor, sistema adminstrar el funcionamiento de la base de datos
PMON -> *process monitor*
SMON ->*system monitor*

**SQL server**
Compite con MySQL y Oracle Databases, e incorpora de manera nativa el estandar SQL, aunque tambien admite su propio lenguaje T-SQL 
1. Protocol Layer (*red, capa de protocolo*)
2. Relational Engine (*motor relacional*)
3. Storage Engine ()
4. SQL Operating System

**Database Engine**
Comprende 2 componentes, motor relaicionar y el motor de almacenamiento
- *Relacional*
	- cmd parcer
	- optimizer
	- query
- *Storage*
	- Archivos primarios: Con informacion de la base de datos
	- Secundarios: 
	- De registro: LDF

**SQL Operating System**
1. Programacion de hilos
2. Sincronizacion de hilos
3. Manejo de memoria y recursos del sistema
4. Manejo de excepciones
5. Puntos muertos

### Actividad 3
### Actividad 4
[Link de referencia - SQL Server](https://www.techonthenet.com/sql_server/index.php)
[Link de referencia - Oracle Databse](https://www.techonthenet.com/oracle/index.php)
[Link de referencia - Oracle Databse 2](https://www.infor.uva.es/~jvegas/cursos/bd/sqlplus/sqlplus.html#loMasSqlPlus)
Principales sentenciass DDL de SQL
- CREATE
	- Permite crear bases de datos, tablas,
- ALTER
	- Modicificar tablas
- DROP
	- Borra tablas, schemas, usuarios o funciones

### Actividad 5
- MySQL
	- Micropocesador de 32 o 64 bits
	- 4 GB de RAM
	-  Monitor de 1024x768
	- Software:
		- .NET 4.5.2
		- Visual
- SQL Server
	- 6 GB de espacio en disco
	- Monitor de 800x600
	- 512 M de RAM
	- Software:
		- Windows 10
		- .NET mas actuales
- Oracle Database
	- Mircroprocesador de 64 bits
	- 2 GB de RAM
	- 2 GB ~ 16 GB de memoria virtual
	- 10 GB de espacio en disco
	- Monitor de 1024x768
	- Software

**Entorno virtualizado**
Maquinas virtuales legales
Soporte de virtualizacion por hardware
Snapshots
Interfaz de RED (Modo puente)
Windows
Considerar espacio compartido

### Instalacion de Oracle Database en Oracle Linux
![[Pasted image 20230309092730.png]]
![[Pasted image 20230309093017.png]]
![[Pasted image 20230309093845.png]]
![[Pasted image 20230309093947.png]]
![[Pasted image 20230309095727.png]]
![[users.png]]


---
version 2
![[Pasted image 20230311205405.png]]
![[Pasted image 20230311205701.png]]
![[Pasted image 20230311205810.png]]
![[Pasted image 20230311210046.png]]
![[Pasted image 20230311210511.png]]
![[Pasted image 20230311210525.png]]
![[chown.png]]
![[Pasted image 20230311210958.png]]
![[ENTORNO.png]]
![[installer.png]]
![[error.png]]
![[root_auto.png]]
![[fin_insta.png]]
![[alfin.png]]

--- 
SQL DEVELOPER
![[sqldeveloper1.png]]
![[sqldeveloper2 1.png]]
![[sqldeveloper3.png]]
![[sqldeveloper4.png]]
![[sqldeveloper5.png]]
![[sqldeveloper6.png]]
![[sqldeveloper7.png]]

---
![[Pasted image 20230318144957.png]]
![[2023-03-18_14-50.png]]
![[recuperarsql1.png]]
![[usuario1.png]]
![[Pasted image 20230318145251.png]]
![[Pasted image 20230318150734.png]]

---
Creacion de tablas
![[Pasted image 20230318151352.png]]
![[Pasted image 20230319093748.png]]
![[Pasted image 20230319095221.png]]
![[Pasted image 20230319095233.png]]
![[Pasted image 20230319095300.png]]

---
Insertar datos
![[Pasted image 20230319095524.png]]
![[Pasted image 20230319101522.png]]

 ![[Pasted image 20230319101853.png]]
![[Pasted image 20230319105931.png]]

![[Pasted image 20230319110216.png]]
![[Pasted image 20230319110610.png]]

![[Pasted image 20230319110740.png]]
![[Pasted image 20230319110846.png]]
![[Pasted image 20230319110930.png]]
![[Pasted image 20230319111451.png]]

---
Tablas sql server
![[Pasted image 20230319171904.png]]
![[Pasted image 20230319171940.png]]
![[Pasted image 20230319173737.png]]
![[Pasted image 20230319173913.png]]
![[Pasted image 20230319174501.png]]
![[Pasted image 20230319174509.png]]
![[Pasted image 20230319175113.png]]
