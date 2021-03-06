# TRABAJO-EXTRA

**AUTOR**

TOAPANTA ANABEL

**TEMA:**  Ejemplo para conexión de base de datos My-SQL con Node-red

**BASE DE DATOS DE CLIENTES DE UN NEGOCIO**

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

Cabe mencionar con anticipación que la instalación de node red se hace atravez de la página NODE-RED sin embargo para que se ejecute bien el programa se debe descargar su implemento que es Node-js.

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/IMG-20210810-WA0036.jpg)
![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/IMG-20210810-WA0037.jpg)

Una ves que se plasmo el concepto procedemos a la instalación de programas los cuales fueron apoyo para la realización del ejemplo.
Uno de ellos es **XAMPP** el cual nos permitirá inicializar  la base de datos la cual es **phMyAdmin** por esta razon  se debe  permitir el acceso  activando en XAMPP  **My-SQL**

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/XAMPP.png)

![image](https://user-images.githubusercontent.com/85134094/128611260-17fda413-cc3e-44ee-aa91-0ee7a8856d81.png)

Una vez dado el acceso a la base de datos procedemos a ingresar a phpMyAdmin y nos registamos

![image](https://user-images.githubusercontent.com/85134094/128611179-501578e4-84e6-4431-9ff0-c083c92f7c1a.png)

![image](https://user-images.githubusercontent.com/85134094/128611223-14b52ffd-8529-4259-97e8-319128777163.png)

Del mismo modo  inicializamos **NODE-RED** con ayude de cmd  como ejecutador del computador para que asi nos proporcione el link que ingresaremos en el navegador .

![image](https://user-images.githubusercontent.com/85134094/128614525-a9764a5c-e657-4ad6-a97f-4acc857400f4.png)

![image](https://user-images.githubusercontent.com/85134094/128614418-6903b6d9-a80a-4847-a29e-5ce8836045ed.png)

Acontinuacióm  procedemos abrir NODE-RED en el servidor de internet con el link proporcionado en el paso anterior.

![image](https://user-images.githubusercontent.com/85134094/128614601-15462123-085d-4847-9456-19fa1d00028f.png)

Ya abierto  **phpMyAdmin** se procede a realizar la base datos  dando clic en NUEVO

![image](https://user-images.githubusercontent.com/85134094/128614832-d554e17c-f17a-4311-93b3-a6fe7e41e732.png)
![image](https://user-images.githubusercontent.com/85134094/128614837-4b831fa3-df83-4959-a12f-ade3fd0fd124.png)

Luego nombramos a nuestra base de datos la cual llamaremos **node-red-temp** y damos clic en crear.

![image](https://user-images.githubusercontent.com/85134094/128615081-1f47639a-29be-4f9d-aa4f-936e38a16f50.png)

Es asi que nuestra base de datos tendra relación con la tabla que pondremos como nombre **clientes** la cual tendra como atributos el id, domicilio y fecha de compra que hace el cliente y clic en crear.

![image](https://user-images.githubusercontent.com/85134094/128782933-47e158a5-6bb2-4cd6-8b3a-d7ab0ab6a706.png)
![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/20210811_204524.jpg)

Ya creado procedemos a ingresar los datos que deseamos ya sea de tipo entero o char.

![image](https://user-images.githubusercontent.com/85134094/128783118-84537e79-5861-4748-9d14-fe22aed9b1e3.png)

Como vemos la base datos ha sido creada satisfactoriamente.

![image](https://user-images.githubusercontent.com/85134094/128783314-1821d24d-91f6-4a84-8506-3965d974b4e9.png)

Despúes de crear nuestra base datos procedemos a dirigirnos a **NODE-RED** para proceder a la conexión de estas dos herramientas. Asi mismo nos dirigimos a la paleta de nodos y empezar con el proceso de conexión con la base de datos.
En primer instancia arrastramos el nodo **Inyect** el cual inyecta un mensaje en un flujo de forma manual o a intervalos regulares. La carga útil del mensaje puede ser de varios tipos, incluidas cadenas u objetos. Como siguiente paso elegimos
el nodo de **function** y lo arrastramos al aréa de trabaji este nodo 9devuelve un objeto de mensaje (o varios objetos de mensaje), pero puede elegir no devolver nada para detener un flujo.

![image](https://user-images.githubusercontent.com/85134094/128784202-337235d0-f580-4586-a84b-324c2bf4807b.png)
![image](https://user-images.githubusercontent.com/85134094/128784212-2b275a17-69de-47e4-ab53-0fcc3b6fcf00.png)

Acontinuación clic en las tres lineas del lado derecho de la pantalla de node red clic en configuraciones ,clic en pallerts y clic en install y como último paso vinculamos el MySQL con Node red desde el nodo principal insert.

![image](https://user-images.githubusercontent.com/85134094/128784493-20edf263-0597-457e-ac37-ab1d823b756a.png)
![image](https://user-images.githubusercontent.com/85134094/128784507-e573a155-9b71-4cbe-8b94-f69621161cb2.png)

Conectamos los dos nodos del aréa de trabajo de la manera que se muestra en la ilustración.

![image](https://user-images.githubusercontent.com/85134094/128784592-80e63703-277a-4d35-9845-bae59ac8a75e.png)

Procedemos a cambiar el topic del nodo Function dando clic en configuaciones al lado derecho del nodo para asi vincular los datos de la base con la función que quiero que los muestre. Por lo cual ingresamos como código lo mostrado acontinuación.

![image](https://user-images.githubusercontent.com/85134094/128784678-021aa5ab-d931-4b25-ac4a-5236ee03107a.png)
![image](https://user-images.githubusercontent.com/85134094/128784766-ab8c581e-9fac-4bb6-af45-b80e48b92e31.png)

Luego buscamos el nodo **Exec** el cual ejecuta el comando del sistema y devuelve su salida.Y lo conectamos en el medio del nodo **Insert** (entrada de datos) y **Function** (salida de datos).

![image](https://user-images.githubusercontent.com/85134094/128784928-f09be29d-fc73-4e09-9d34-01f57276f98e.png)
![image](https://user-images.githubusercontent.com/85134094/128785003-0f0cecb4-f3bd-4da3-9650-564ff7d0a662.png)
![image](https://user-images.githubusercontent.com/85134094/128785282-e5ae3c26-1a19-4950-90fb-90850b9aef51.png)

Luego procedemos a cambiar el topic para que permita la salida correcta de los datos ingresados desde la base de datos.

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/20210811_203749.jpg)
![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/IMG-20210811-WA0016.jpg)

Como siguiente paso tenemos seleccionamos y arrastramos el nodo **MySQL** para insertar valores a una base de datos y damos dobles clic en nodo el cual nos propone seleccionar la base de datos con la cual deseamos trabajar la cual es **time**.

![image](https://user-images.githubusercontent.com/85134094/128785811-1d86d9e9-ec99-4394-89d9-6a9063b181cd.png)
![image](https://user-images.githubusercontent.com/85134094/128785817-e5182613-416e-4e75-a91a-e923cbff444d.png)

Acontinuación arrastramos el último nodo el cual es **Debug** el cual se utiliza para mostrar mensajes en la barra lateral Debug dentro del editor y lo conectamos entre si.

![image](https://user-images.githubusercontent.com/85134094/128785966-8684ab4d-45ef-4ca9-ba78-4b86ca768f08.png)
![image](https://user-images.githubusercontent.com/85134094/128785973-caca0e33-d8d4-4518-854a-4d76519775d0.png)

Se procede con la configuración del topic del nodo **MySQL** el cual relaciona los datos de la base con Node-red para lo cual implementamos el código siguiente en el topic del nodo.

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/20210811_203749.jpg)

Por último editamos el mismo nodo entramos a propiedades y editamos el usuario y contraseña para asi vincular este nodo con la base de datos.

![image](https://user-images.githubusercontent.com/85134094/128786316-87bbfd4b-a3f7-4dee-963b-e92e5a0d91a2.png)
![image](https://user-images.githubusercontent.com/85134094/128786337-ad58ac4e-0cfd-4ddb-a9f1-ef696a88f93c.png)

Como penúltimo paso tenemos renombrar el nodo MySQL como **db** y ponemos el nombre de la base de datos en la que queremos trabajar.

![image](https://user-images.githubusercontent.com/85134094/128786452-1d593fc9-61a8-4cb5-aa1d-bc3e65c74397.png)
![image](https://user-images.githubusercontent.com/85134094/128786480-8870217e-cc5b-4fb6-bb58-86ab48aa9b99.png)
![image](https://user-images.githubusercontent.com/85134094/128786557-3c808513-3f1a-41cd-9c88-e49454fe1f13.png)
![image](https://user-images.githubusercontent.com/85134094/128786644-78556c12-e5f3-479a-9316-dd0eaa00ab91.png)

Por último paso tenemos la ejecución del Node-Red y se observa que está correctamente creada. 

![image](https://user-images.githubusercontent.com/85134094/128786758-fdfc8bce-e3b3-444e-b66b-ef1470f2340b.png)
![image](https://user-images.githubusercontent.com/85134094/128786838-ca15b94d-17e9-4621-8e84-db1d3ab2faf3.png)

Luego procedmos a cambiar el topic de la funcion según los datos que ingresamos cada vez que editamos este.

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/20210811_203749.jpg)

Seguidamente damos clic en diploy y en el nodo inyect para que se inserte el dato de la misma manera esto se puede comprobar su ejecución al lado derecho de la ventana de este modo.El cual nos confirma que el dato se ingresado correctamente. 

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/20210811_205657.jpg)
![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/IMG-20210811-WA0017.jpg)

Por último verificamos que lo ingresado en el topic de function se haya copiado correctamente en la base de datos.

![](https://github.com/Anabeltoapanta/TRABAJO-EXTRA/blob/main/DESARROLLO/IMG-20210811-WA0016.jpg)

Ilustración final del ejemplo propuesto

![image](https://user-images.githubusercontent.com/85134094/128786948-34d047f6-1b51-4fb5-8ff4-73ee90abd548.png)

**VIDEO DE LA PARTE PRACTICA**

https://youtu.be/3n04JFXlVyI

**CONCLUSIÓN**

* Podemos ver que Node-Red vinculador con una base de datos en My-SQL es una herramienta muy util para organizar imformación y hacer atravez de forma mas rapida y sencila.
* En esta ocasión, con tan solo unas pocas líneas de código hemos podido conectar a una base de datos y obtener por consola los resultados deseados. 
* En conclusión nos ayudo a familiarizarnos con una base de datos y su manejo mediante Node-Red.
