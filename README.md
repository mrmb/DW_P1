# Data Warehouse Fase 1
------------------------------------------------------------------------------
**Proyecto:** Data Warehouse para AdventureWorks
**Tema:** SQL, Base de Datos, DW
**Fecha de Entrega:** Indicada en la asignación del GES
**Grupo:** Grupos de 4 o 5 personas
**Calificación:** Presentación de entregables en clase
**Adventure Works DB:** [DB link](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2017.bak)
------------------------------------------------------------------------------

**ATENCIÓN:** Todos los proyectos consumen tiempo, así que trate de empezar lo más pronto que pueda. Recuerde que el proyecto es en GRUPOS, es decir que no puede trabajar junto a otros compañeros de otros grupos.

## Data Warehouse para AdventureWorks
Para este proyecto usted implementará un Data Warehouse con todas las etapas que este conlleva, al ser un proyecto que tomara tiempo, el mismo se divide en dos fases. Este documento explica la primera fase. 

Se utilizará una base de datos publica con el fin de poner en práctica la teoría del curso. AdventureWorks es una base de datos publica que cuenta con 65 tablas, las tablas tienen relación entre sí y representa información de ventas, empleados, compras, etc. Su grupo deberá analizada la base de datos y aplicar la metodología vista en clase para la implementación del DW. 

# Su proyecto
**En general:** ¿Qué es lo que tiene que hacer en su proyecto? Para esta fase se debe implementar de forma correcta 7 de las etapas descritas en la metodología vista en clase para la implementación de un DW, dichas etapas se describen en este documento. 

## Objetivos:
El objetivo es poner en práctica los conocimientos adquiridos en clase para la implementación correcta de cada una de las etapas descritas en la metodología: **Kimball Business Dimensional Lifecycle** y contar con una base para la implementación correcta de la segunda fase del proyecto. 


Kimball Business Dimensional Lifecycle Diagram: 
![alt text](https://www.kimballgroup.com/wp-content/uploads/2012/06/kimball-core-concepts-021.png "Diagram 1")


## Especificaciones:
Aventure Works es una base de datos normalizada, por lo cual existen llaves primarias y foráneas que se deben analizar para determinar la relación que existe en la base de datos. Al obtener información sobre la base de datos, se busca la creación de un Data Warehouse, En la segunda fase se deberá de exponer todo el proyecto, es por ello que en esta fase se solicitaran entregables para cada etapa con el fin de ayudarlo en la presentación final. 

## 1. Project Planning:
Para esta etapa, su grupo debe de crear una planificación en cualquier herramienta de planificación, con el fin de listar todas las tareas a realizar por el proyecto. 
       
       Entregable: Project management plan para el Proyecto Data Warehouse para AdventureWorks.

## 2. Business Requierements Definition:
Para esta etapa su grupo debe analizar la base de datos AdventureWorks y definir los/el Data Marts a implementar con sus tablas y campos correspondientes por cada tabla. 
Tip: Considerar utilizar las preguntas que se encuentran en las presentaciones. 

    Entregable: Documento en donde se encuentran las respuestas a cada una de las preguntas que se encuentran en las presentaciones del curso. Como no es factible tener contacto con la empresa, pueden definir a interés propio el objetivo de hacer el DW.

## 3. Technical Architecture Design
Para esta etapa deben de definir la arquitectura del sistema, se debe de considerar la experiencia del equipo y tomar en cuanta las sugerencias que se brindan en clase. 

    Entregable: Documento en donde indique las tecnologías a utilizar y la razón de usar dicha tecnología. 

## 4. Dimensional Modeling
Para esta etapa, se debe de implementar los Data Marts, todos ellos basados en las respuestas que se obtuvieron de la etapa 2.

    Entregable: 
        Listado de Data Mart a utilizar y la razón de utilizar cada uno de ellos. 
        Implementar el modelo de relación para cada Data Mart.


## 5. Product Selection and Installation
Para esta etapa se debe de instalar los componentes necesarios en el servidor a utilizar que consideren mas conveniente. 

    Entregable: Documento donde se liste las marcas o servicios que se utilizaran y la razón de utilizar cada una de las tecnologías. 

## 6. Physical design
Para esta etapa, se debe de implementar los Data Marts en algún motor de base de datos.

    Entregable: Script con los Data Marts 

## 7. Data Storage Design and Development
Para esta etapa se debe de almacenar los scripts de la etapa anterior en un servidor, este servidor debe ser estipulado en la etapa 3. 
