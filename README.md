### Universidad Nacional Abierta y a Distancia – UNAD
### BigData – Tarea 4: Almacenamiento y Consultas de Datos en Big Data
#### Por: Martha Jimenez Rojas


### Descripción del proyecto

Este repositorio contiene el desarrollo de la implementación MongoDB correspondiente a la Tarea 4 del curso Big Data. Aquí se incluye el caso de uso, el dataset utilizado y el archivo donde se encuentran las consultas realizadas.

### Caso de uso

El dataset corresponde a los subsidios de vivienda asignados en todos los departamentos y municipios de Colombia. Esta estructura hace que el tipo de base de datos más adecuado sea una base de datos NoSQL orientada a documentos, como MongoDB.
El caso de uso propuesto consiste en una plataforma institucional para la consulta y análisis de subsidios de vivienda, utilizada por entidades gubernamentales o territoriales. La plataforma debe permitir realizar búsquedas flexibles por departamento, municipio, año o programa, así como generar reportes estadísticos y analizar tendencias históricas en la asignación de subsidios.
MongoDB es ideal para este caso porque permite almacenar cada subsidio como un documento independiente, manejar datos semiestructurados provenientes de archivos CSV y ejecutar consultas analíticas mediante el Aggregation Pipeline. Además, soporta grandes volúmenes de información y consultas dinámicas, características necesarias para un sistema de análisis de datos públicos en el contexto de vivienda.


### Contenido del repositorio

#### 1. Dataset utilizado
Subsidios_De_Vivienda_Asignados_20251122.csv
Contiene los datos utilizados para poblar la base de datos en MongoDB. Es el archivo base empleado para la carga inicial de registros.

#### 2. Archivo de consultas

consultas_subsidios_vivienda.txt
Contiene todas las consultas implementadas en MongoDB Compass, las cuales están escritas en MongoDB Query Language (MQL) y se ejecutaron directamente en MongoDB Compass sin scripts externos.

