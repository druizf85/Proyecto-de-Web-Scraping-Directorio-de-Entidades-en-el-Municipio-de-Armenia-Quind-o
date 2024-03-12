# Proyecto de Web Scraping - Directorio de Entidades en el Municipio de Armenia Quindío

Este proyecto muestra la solicitud a una API en la cual se encuentra la información de un conjunto de datos que muestra la información de los Proveedores del SECOP II que se encuentran registrados en el municipio de Armenia, Quindío.

En este ejercicio se realizan los siguientes procedimientos:

-	Construir una URL para hacer una solicitud a una API web.	
-	Hacer una solicitud HTTP GET a la URL construida utilizando la biblioteca requests.
-	Creación de una Dataframe con pandas de la información que se extrae de la web.
-	Agrupaciones, estandarizaciones y transformaciones a la base de datos.
-	Gráfico de torta con información para análisis.
-	Fijar una fecha de actualización del día de hoy.

Fuente de datos:

Se tomó como fuente de datos la información del conjunto de datos de datos abiertos llamado “SECOP II - Proveedores Registrados - Armenia (Quindío)”, este conjunto de datos es tomado en función del conjunto de datos de los proveedores registrados en SECOP y es administrado por Colombia Compra Eficiente, con una fecha de actualización diaria.

	SECOP II - Proveedores Registrados
https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-II-Proveedores-Registrados/qmzu-gj57/data 

	SECOP II - Proveedores Registrados - Armenia (Quindío)
https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-II-Proveedores-Registrados-Armenia-Quind-o-/56sy-nvip/about_data 

El resultado final de este proceso es obtener una base de datos actualizada, ya que las fuentes de información se actualizan diariamente, y una automatización de este proceso de solicitud y transformación de la información para el uso final de la base de datos en un archivo Excel, el cual tiene como nombre ‘DIRECTORIO ARMENIA’.
