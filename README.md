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


Una vez dado el acceso a la base de datos procedemos a ingresar a phpMyAdmin y nos registamos

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

Es asi que nuestra base de datos tendra relación con la tiempo en este paso seleccionaremos el numero de columnas que va a contener y clic en crear.

![image](https://user-images.githubusercontent.com/85134094/128782933-47e158a5-6bb2-4cd6-8b3a-d7ab0ab6a706.png)
![image](https://user-images.githubusercontent.com/85134094/128783565-cdb94f36-583e-4f3f-88c0-67ca1a320b9b.png)

Ya creado procedemos a ingresar los datos que deseamos ya sea de tipo entero o char.

![image](https://user-images.githubusercontent.com/85134094/128783118-84537e79-5861-4748-9d14-fe22aed9b1e3.png)

![image](https://user-images.githubusercontent.com/85134094/128783314-1821d24d-91f6-4a84-8506-3965d974b4e9.png)



![image](https://user-images.githubusercontent.com/85134094/128784202-337235d0-f580-4586-a84b-324c2bf4807b.png)
![image](https://user-images.githubusercontent.com/85134094/128784212-2b275a17-69de-47e4-ab53-0fcc3b6fcf00.png)


![image](https://user-images.githubusercontent.com/85134094/128784493-20edf263-0597-457e-ac37-ab1d823b756a.png)
![image](https://user-images.githubusercontent.com/85134094/128784507-e573a155-9b71-4cbe-8b94-f69621161cb2.png)


![image](https://user-images.githubusercontent.com/85134094/128784592-80e63703-277a-4d35-9845-bae59ac8a75e.png)


![image](https://user-images.githubusercontent.com/85134094/128784678-021aa5ab-d931-4b25-ac4a-5236ee03107a.png)
![image](https://user-images.githubusercontent.com/85134094/128784766-ab8c581e-9fac-4bb6-af45-b80e48b92e31.png)

![image](https://user-images.githubusercontent.com/85134094/128784928-f09be29d-fc73-4e09-9d34-01f57276f98e.png)

![image](https://user-images.githubusercontent.com/85134094/128785003-0f0cecb4-f3bd-4da3-9650-564ff7d0a662.png)

![image](https://user-images.githubusercontent.com/85134094/128785282-e5ae3c26-1a19-4950-90fb-90850b9aef51.png)


![image](https://user-images.githubusercontent.com/85134094/128785360-581b4656-08f6-412d-82f5-93d366cc70df.png)
![image](https://user-images.githubusercontent.com/85134094/128785467-815ad1aa-5aec-4909-8fac-5474099ab449.png)

![image](https://user-images.githubusercontent.com/85134094/128785531-dd9841e9-92e6-44ab-ab5d-553149e6f65b.png)
![image](https://user-images.githubusercontent.com/85134094/128785648-3215dbb3-7f57-4ba0-9aac-f372fa7ae329.png)

![image](https://user-images.githubusercontent.com/85134094/128785811-1d86d9e9-ec99-4394-89d9-6a9063b181cd.png)
![image](https://user-images.githubusercontent.com/85134094/128785817-e5182613-416e-4e75-a91a-e923cbff444d.png)

![image](https://user-images.githubusercontent.com/85134094/128785966-8684ab4d-45ef-4ca9-ba78-4b86ca768f08.png)
![image](https://user-images.githubusercontent.com/85134094/128785973-caca0e33-d8d4-4518-854a-4d76519775d0.png)

![image](https://user-images.githubusercontent.com/85134094/128786136-e6f37ea6-4673-4489-bf5f-a737770dc748.png)
![image](https://user-images.githubusercontent.com/85134094/128786149-65ea528a-fecf-41b5-8074-16000ed41957.png)

![image](https://user-images.githubusercontent.com/85134094/128786316-87bbfd4b-a3f7-4dee-963b-e92e5a0d91a2.png)
![image](https://user-images.githubusercontent.com/85134094/128786337-ad58ac4e-0cfd-4ddb-a9f1-ef696a88f93c.png)

![image](https://user-images.githubusercontent.com/85134094/128786452-1d593fc9-61a8-4cb5-aa1d-bc3e65c74397.png)
![image](https://user-images.githubusercontent.com/85134094/128786480-8870217e-cc5b-4fb6-bb58-86ab48aa9b99.png)

![image](https://user-images.githubusercontent.com/85134094/128786557-3c808513-3f1a-41cd-9c88-e49454fe1f13.png)
![image](https://user-images.githubusercontent.com/85134094/128786644-78556c12-e5f3-479a-9316-dd0eaa00ab91.png)

![image](https://user-images.githubusercontent.com/85134094/128786758-fdfc8bce-e3b3-444e-b66b-ef1470f2340b.png)

![image](https://user-images.githubusercontent.com/85134094/128786838-ca15b94d-17e9-4621-8e84-db1d3ab2faf3.png)

![image](https://user-images.githubusercontent.com/85134094/128786948-34d047f6-1b51-4fb5-8ff4-73ee90abd548.png)




