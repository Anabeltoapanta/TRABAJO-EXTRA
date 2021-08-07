# TRABAJO-EXTRA

**TEMA:** Ejemplo para conexión de base de datos My-SQL con Node-red

**1.OBJETIVOS**

**Objetivo general**

* Diseñar y crear una conexión de base de datos My-SQL con ayuda de node-red

**Objetivos Específicos**

* Organizar y almacenar datos para su fácil manejo.
*  Explicar como funciona una base de datos con Node red

**2.DESARROLLO**

Antes de dar una explicación de como se realizo el empleo en primera instancia plasmaremos conceptos básicos de que es My-SQL y Node-Red y la relación que tienen al crear una base de datos.

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/MY-SQL.png) My-SQL : Es un sistema de gestión de bases de datos que sirve para almacenar toda la información que se desee en bases de datos 

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/NODE-RED.png) Node red : es una herramienta de programación visual. Muestra visualmente las relaciones y funciones entre datos

Una ves que se plasmo el concepto procedemos a la instalación de programas los cuales fueron apoyo para la realización del ejemplo.
Uno de ellos es **XAMPP** el cual nos permitirá inicializar  la base de datos la cual es **phMyAdmin** por esta razon  se debe  permitir el acceso  activando en XAMPP  **My-SQL**

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/XAMPP.png)

![image](https://user-images.githubusercontent.com/85134094/128611260-17fda413-cc3e-44ee-aa91-0ee7a8856d81.png)


Una vez  dado el acceso a la base de datos  procedemos a  ingresar a phpMyAdmin  y nos registamos

![image](https://user-images.githubusercontent.com/85134094/128611179-501578e4-84e6-4431-9ff0-c083c92f7c1a.png)

![image](https://user-images.githubusercontent.com/85134094/128611223-14b52ffd-8529-4259-97e8-319128777163.png)

Del mismo modo  inicializamos **NODE-RED** con ayude de cmd del computador  para que asi nos proporcione el link que ingresaremos en el navegador .

![image](https://user-images.githubusercontent.com/85134094/128614525-a9764a5c-e657-4ad6-a97f-4acc857400f4.png)

![image](https://user-images.githubusercontent.com/85134094/128614418-6903b6d9-a80a-4847-a29e-5ce8836045ed.png)

Acontinuacióm  procedemos abrir NODE-RED en el servidor de internet.

![image](https://user-images.githubusercontent.com/85134094/128614601-15462123-085d-4847-9456-19fa1d00028f.png)

Ya abierto  **phpMyAdmin** se procede a realizar la base datos  dando clic en NUEVO

![image](https://user-images.githubusercontent.com/85134094/128614832-d554e17c-f17a-4311-93b3-a6fe7e41e732.png)
![image](https://user-images.githubusercontent.com/85134094/128614837-4b831fa3-df83-4959-a12f-ade3fd0fd124.png)

Luego nombramos a nuestra base de datos y damos clic en crear.

![image](https://user-images.githubusercontent.com/85134094/128615081-1f47639a-29be-4f9d-aa4f-936e38a16f50.png)

Es asi que nuestra base de datos tendra relación con la temperatura en este paso seleccionaremos el numero de columnas que va a contener.

![image](https://user-images.githubusercontent.com/85134094/128615187-4031aec1-1042-41e3-871d-d74cd680566e.png)


![image](https://user-images.githubusercontent.com/85134094/128615165-762e2c13-4950-4290-ab7a-cb79c67b9841.png)



