
<img src="./doc/Captura%20de%20pantalla%20(901).png" style="width: 100%; height: 80%"/>

# Micro Front End Componentes de MicroElectrónica.
Aplicación Web Micro Front End MicroElectrónica implementando React, Html5, Scss, Highcharts, Bootstrap, Spring Boot, Spring MVC, Spring Data JPA, SpringFox, Swagger UI, Maven, Lombok, Postman, Log4j, Git, SQLDeveloper, Oracle XE 21c y Otras Tecnologías.
* [Repositorio ApiRest_Microcomponentes_SpringBoot](https://github.com/andresWeitzel/ApiRest_Microcomponentes_SpringBoot)
* [Repositorio db_Microcomponentes_OracleXE](https://github.com/andresWeitzel/db_Microcomponentes_OracleXE)


<br>

## Índice 📜

<details>
 <summary> Ver </summary>
 
 <br>
 
### Sección 1) Descripción, Tecnologías y Dependencias 

 - [1.0) Descripción del Proyecto.](#10-descripción-)
 - [1.1) Ejecución del Proyecto.](#11-ejecución-del-proyecto-)
 - [1.2) Tecnologías.](#12-tecnologías-)

  
### Sección 2) Endpoints y Recursos 
 
 - [2.0) EndPoints.](#endpoints-)
 - [2.1) Recursos y Servicios.](#recursos-y-servicios-)
  
  
### Sección 3) Prueba de Funcionalidad y Referencias
 
 - [3.0) Prueba de Funcionalidad.](#30-prueba-de-funcionalidad-)
 - [3.1) Referencias.](#31-referencias-)
	  
  
  
<br>

</details>




<br>

## Sección 1) Descripción, Tecnologías y Dependencias 


### 1.0) Descripción [🔝](#índice-) 

<details>
  <summary>Ver</summary>
 
 <br>
 
* Esta aplicación ha sido desarrollada para la gestión de microcomponentes ( transistores, capacitores, placas, etc). También se ha pensado originalmente desarrollar una sección para la gestión de compras, pedidos, etc. Queda pendiente de implementar.
* Todos los formularios aplican validaciones de carácteres, longitudes, tamaños, valores numéricos, valores mal formados, email, contraseña, url de imágenes, etc.
* Se implementa Paginación Completa.
* Se aplican varios filtros de búsqueda, como por ej: Búsqueda de microcomponentes de forma genérica, según tipo, clase, según el campo deseado, etc... permitiendo coincidencias de carácteres, números y palabras.
* Para la experiencia de usuario se utiliza Popupts, Loaders, etc.
* Es posible descargar el Listado de microcomponentes Paginado en formato xlsx (excel), csv y pdf.
* Entre Otros Recursos Disponibles.
* Aclaración : Este Microfrontend no es responsive. El enfoque es la funcionalidad de la aplicación, la maquetación es totalmente aplicable en relación al tiempo de disponibilidad que se emplee.

<br>

</details>



### 1.1) Ejecución del Proyecto [🔝](#índice-)

<details>
  <summary>Ver</summary>
  
 <br>  
 
* Descargamos y levantamos [Oracle XE](https://www.oracle.com/database/technologies/appdev/xe.html) para ejecutar los servicios de base de datos.
* Abrimos una terminal y clonamos el [repo de base de datos](https://github.com/andresWeitzel/db_Microcomponentes_OracleXE).
* Creamos y configuramos una conexión de oracle para la ejcución de los archivos de db.
* Para más info. consultar repositorio respectivo
* Descargamos [Spring tool suite 4](https://spring.io/tools)
* Desde sts u otro ide abrimos una terminal y creamos un entorno de trabajo o workspace.
* Clonar el Proyecto
```git
git clone https://github.com/andresWeitzel/ApiRest_Microcomponentes_SpringBoot
```
* Click der sobre el proyecto --> Run as --> Spring Boot App
* Ya tenemos corriendo nuestra api desde tomcat. El url de la app para la ejecución de los endpoint's lo visualizamos desde consola.
* Pendiente

<br>

</details>




### 1.2) Tecnologías [🔝](#índice-)

<details>
  <summary>Ver</summary>
 
 <br>

| Tecnologías FRONTEND | Versión | Finalidad
| ------------- | ------------- | ------------- |
| [HTML](https://www.w3schools.com/html/) |  5.0 | Lenguaje de Hipertexto | 
| [Css](https://www.w3schools.com/css/) |  3.0 | Lenguaje de hojas de estilo para presentación de documentos.  |
| [Scss](https://sass-lang.com/) | 1.57 | Preprocesador de css.  |
| [React](https://ru.legacy.reactjs.org/) |  18.2.0 | Librería js | 
| [React CLI](https://ru.legacy.reactjs.org/) | 0.3.1 | Herramienta de Angular para depurar, crear, publicar, etc Apps |
| [Axios](https://www.npmjs.com/package/axios) |  0.27.2 |  Cliente HTTP Basado en Promesas para el navegador |
| [Bootstrap](https://getbootstrap.com/) | 5.1  | FrameWork Web Diseño y Desarrollo de Apps |
| [Visual Studio Code](https://code.visualstudio.com/download) | 1.51.1  | Entorno de Desarrollo |
| Otros | - | - |


| Tecnologías BACKEND | Versión | Finalidad
| ------------- | ------------- | ------------- |
| [Java]( https://www.oracle.com/java/technologies/javase/jdk12-archive-downloads.html) |   12.0.2 | JDK |
| [Spring Tool Suite 4](https://spring.io/blog/2021/06/21/spring-tools-4-11-0-released) | 4.9.0  | IDE |
| [Spring Boot](https://spring.io/) |   2.6.4  | Framework |
| [Spring Boot Data JPA](https://spring.io/projects/spring-data-jpa)  | 2.6.3 | Mapeo de objetos y persistencia en la db |
| [Spring Security](https://spring.io/projects/spring-security) | 2.6.7 | Servicios de Seguridad |
| [JSON Web Token](https://jwt.io/) | 0.9.1 | Creación de tokens de acceso | 
| [Maven](https://maven.apache.org/) |  4.0.0 | Gestor de Proyectos |
| [Postman](https://www.postman.com/) | 9.4.1 | Test de Apis |
| [Lombok](https://projectlombok.org/) | 1.18.22 | Automatización de Código | 
| [Open-Api](https://www.openapis.org/) | 1.6.4 | Documentación de la Api | 
| [UI Swagger](https://swagger.io/tools/swagger-ui/) | 1.6.4 | Visualización y Gestión de la Api | 
| [GNU bash / Terminal](https://www.gnu.org/software/bash/) | 4.4.23  | Bash / Terminal para el manejo e implementación de Git integrado al Spring Tool Suite |
| [Git](https://git-scm.com/) | 2.29.1  | Control de Versiones |
| Otros | - | - |


| Tecnologías DATABASE | Versión | Finalidad
| ------------- | ------------- | ------------- |
| [OracleXE21c]( https://www.oracle.com/database/technologies/xe-downloads.html) | 21.0 | SGDB |
| [SqlDeveloper](https://www.oracle.com/ar/database/technologies/appdev/sqldeveloper-landing.html) |  22.2.1 |	Gestor para el SGDB Oracle |
| Otros | - | - |

<br>

</details>



<br>


## Sección 2) EndPoints y Recursos

### 2.0) EndPoints [🔝](#índice-)

<details>
 <summary>Ver</summary>

<br>

</details>





### 2.1) Recursos y Servicios [🔝](#índice-)

<details>
 <summary>Ver</summary>
  

<br>

</details>





<br>


## Sección 3) Prueba de Funcionalidad y Referencias


### 3.0) Prueba de Funcionalidad [🔝](#índice-)

<details>
 <summary>Ver</summary>

### Listado de Productos Paginados
![Index app](./doc/Captura%20de%20pantalla%20(901).png)
![Index app](./doc/Captura%20de%20pantalla%20(902).png)
![Index app](./doc/Captura%20de%20pantalla%20(903).png)


</br>

#### Documentación Gráfica Acotada por razones de simplificación de documentación. Visualizar los videos desde la PlayList acerca de las Pruebas de Funcionalidad de la aplicación.

 <br>

</details>




### 3.1) Referencias [🔝](#índice-)

<details>
 <summary>Ver</summary>

### Documentación Oficial

* [Java-JDK 12](https://www.oracle.com/java/technologies/javase/jdk12-archive-downloads.html)
* [Bootstrap](https://getbootstrap.com/)
* [React](https://reactjs.org/docs/getting-started.html)
* [React CLI](https://www.npmjs.com/package/react-cli)
* [OracleXE21c](https://www.oracle.com/database/technologies/appdev/xe.html)
* [SQLDeveloper](https://www.oracle.com/database/sqldeveloper/)
* [Maven Repository](https://mvnrepository.com/) 
* [PostMan](https://www.postman.com/downloads/) 
* [Visual Studio Code](https://code.visualstudio.com/download)
* [Spring Tool Suite 4](https://spring.io/tools)
* [Git](https://git-scm.com/docs)


</details>

<br>











