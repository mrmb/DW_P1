# Data Warehouse Fase 2

**Proyecto:** Data Warehouse para AdventureWorks\
**Tema:** SQL, Base de Datos, DW\
**Fecha de Entrega:** 03/04/2020\
**Hora de Entrega:** Virtual por Zoom de 6 PM a 7 PM\
**Grupo:** Grupos de 4 o 5 personas\
**Calificación:** Presentación de entregables en Zoom\
**Adventure Works DB:** [link](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2017.bak)



**ATENCIÓN:** Todos los proyectos consumen tiempo, así que trate de empezar lo más pronto que pueda. Recuerde que el proyecto es en GRUPOS, es decir, no puede trabajar junto a otros compañeros de otros grupos.

## Data Warehouse para AdventureWorks
Para esta fase su grupo debe de continuar con la fase 1 del proyecto. Usted debe de completar las etapas que no fueran implementadas en la primera fase. Este documento explica la segunda fase. 

Se utilizará una base de datos publica con el fin de poner en práctica la teoría del curso. AdventureWorks es una base de datos publica que cuenta con 65 tablas, las tablas tienen relación entre sí y representa información de ventas, empleados, compras, etc. Su grupo deberá mejorar el diseño propuesto para el Data Warehouse en la primera fase y enfocarse que el mismo sea un modelo estrella. 

# Su proyecto
**En general:** ¿Qué es lo que tiene que hacer en su proyecto? Para esta fase debe implementar los procesos de transformación (ETL) y tener una interfaz gráfica en donde se pueda ver el resultado de la(s) tabla(s) de hechos y ser auxiliada por tablas de dimensiones. 

## Objetivos:
El objetivo es poner en práctica los conocimientos adquiridos en clase sobre Pentaho y Data Studio de Google, así como completar el diagrama Kimball expuesto a continuación.   

Kimball Business Dimensional Lifecycle Diagram: 
![alt text](https://www.kimballgroup.com/wp-content/uploads/2012/06/kimball-core-concepts-021.png "Diagram 1")


## Especificaciones:
Con base a la fase previa ya desarrollada, se busca la implementación de los ETLs en alguna herramienta que permita extraer, transformar y cargar datos de la base de datos Adventure Works a las estructuras ya creadas para el DW. 

Una vez los datos estén cargados dentro del DW, se debe brindar un módulo que permita hacer el mantenimiento de los mismo y por último se busca la implementación de un reporte (dashboard) en donde se pueda explicar la etapa de requerimientos planteados en la primera fase. 

Como parte del documento a entregar, se debe incluir todo el documento que se desarrolló en la fase 1 y agregarlo las etapas de la fase 2:

## 1. Project Planning [Fase 1]:
Para esta etapa, su grupo debe de crear una planificación en cualquier herramienta de planificación, con el fin de listar todas las tareas a realizar por el proyecto. 
       
       Entregable: Project management plan para el Proyecto Data Warehouse para AdventureWorks.

## 2. Business Requierements Definition [Fase 1]:
Para esta etapa su grupo debe analizar la base de datos AdventureWorks y definir los/el Data Marts a implementar con sus tablas y campos correspondientes por cada tabla. 
Tip: Considerar utilizar las preguntas que se encuentran en las presentaciones. 

    Entregable: Documento en donde se encuentran las respuestas a cada una de las preguntas que se encuentran en las presentaciones del curso. Como no es factible tener contacto con la empresa, pueden definir a interés propio el objetivo de hacer el DW.

## 3. Technical Architecture Design [Fase 1]:
Para esta etapa deben de definir la arquitectura del sistema, se debe de considerar la experiencia del equipo y tomar en cuanta las sugerencias que se brindan en clase. 

    Entregable: Documento en donde indique las tecnologías a utilizar y la razón de usar dicha tecnología. 

## 4. Dimensional Modeling [Fase 1]:
Para esta etapa, se debe de implementar los Data Marts, todos ellos basados en las respuestas que se obtuvieron de la etapa 2.

    Entregable: 
        Listado de Data Mart a utilizar y la razón de utilizar cada uno de ellos. 
        Implementar el modelo de relación para cada Data Mart.


## 5. Product Selection and Installation [Fase 1]:
Para esta etapa se debe de instalar los componentes necesarios en el servidor a utilizar que consideren más conveniente. 

    Entregable: Documento donde se liste las marcas o servicios que se utilizaran y la razón de utilizar cada una de las tecnologías. 

## 6. Physical design [Fase 1]:
Para esta etapa, se debe de implementar los Data Marts en algún motor de base de datos.

    Entregable: Script con los Data Marts 

## 7. Data Storage Design and Development [Fase 1]:
Para esta etapa se debe de almacenar los scripts de la etapa anterior en un servidor, este servidor debe ser utilizado para la etapa 2.

	Entregable: Credenciales para acceso de servidor. 

## 8. ETL [Fase 2]:
Para esta etapa se deben crear transformaciones en alguna herramienta que le ayude a extraer, transformar y cargar datos del sistema AdventureWorks, se le recomiendo utilizar Pentaho, esto le permitirá obviar tener grandes conocimientos de SQL y proceder con las transformaciones como se vieron en las últimas clases. También puede utilizar la herramienta que considere más conveniente, siempre y cuando pueda explicar el proceso que utiliza la herramienta para generar la transformación.

	Entregable: Archivo(s) de las transformaciones. 

## 9. Maintenance [Fase 2]:
Para esta etapa, se busca poder darle mantenimiento a la(s) tabla(s) de hechos como a las tablas de dimensiones. Puede utilizar el paso "Update" del kit de Pentaho para esta tarea, el objetivo es mapear una llave primaria de las tablas de sistemas con el data warehouse, con el fin de determinar si existe algún cambio en el sistema AdventureWorks y que este mismo se vea reflejado al ser ejecutada la transformación. 

	Entregable: Archivo(s) de las actualizaciones. 


## 10. Dashboard [Fase 2]:
Para esta etapa, se busca que pueda implementar un reporte que responda las preguntas estipuladas en la etapa 2. Se debe poder filtrar por fechas y por lo mínimo un campo que se encuentre en alguna de las dimensiones. 

	Entregable: Archivo(s) de las transformaciones. 

