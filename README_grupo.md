# Práctica Grupal: SQL Murder

**¡Encuentra al asesino!**

## Descripción.


Este proyecto aborda un caso de asesinato ocurrido el 15 de enero de 2018 en SQL City, desafiando a los participantes a utilizar sus habilidades en SQL para descubrir al culpable. A través de una serie de etapas los participantes navegan por una base de datos compleja, extrayendo información crucial y conectando pistas para resolver el misterio.


### Resumen de los Pasos Seguidos

* Recuperación del Informe del Crimen: Iniciamos recuperando el informe del crimen correspondiente de la base de datos de la policía, basándonos en la fecha y el lugar del suceso 

* Análisis de Datos Iniciales: Investigamos los primeros datos sobre el crimen, incluyendo direcciones y declaraciones iniciales, para obtener una comprensión básica del caso.
  
* Entrevistas a Sospechosos: Exploramos las entrevistas realizadas a los sospechosos identificados para recabar más detalles y pistas.

* Revisión de Registros de Gimnasio: Analizamos los registros de entrada en el gimnasio, obteniendo información sobre los movimientos y actividades de los sospechosos.

* Investigación de Suscripciones de Gimnasio: Con los datos obtenidos, investigamos las suscripciones de gimnasio de los sospechosos, lo que nos llevó a un sujeto que concordaba con la descripción del asesino.

* Consultas Avanzadas: Para un análisis más profundo, creamos consultas SQL que agrupan todos los datos recopilados, permitiéndonos hacer conexiones cruciales y acercarnos a la solución del caso.
  
## Herramientas y Recursos Utilizados

* Python: Lenguaje de programación utilizado para la manipulación de datos y ejecución de consultas SQL.
* SQLite3: Biblioteca de Python utilizada para interactuar con la base de datos SQL.
* Pandas: Biblioteca de Python para el análisis y manejo eficiente de datos.
* Base de Datos: sql-murder-mystery.db, una base de datos especialmente diseñada para esta práctica, conteniendo tablas relevantes al caso de asesinato.





# Práctica Grupal: Diseño de Base de Datos

## Descripción

Esta práctica grupal tiene como objetivo el diseño de un modelo de base de datos relacional para la gestión de proveedores y suministros de piezas. El diseño debe permitir un seguimiento eficaz de las piezas suministradas, incluyendo la cantidad y la fecha de suministro, así como el histórico completo de las transacciones. Se debe tener en cuenta que una pieza puede ser suministrada por varios proveedores y pertenecer a una sola categoría.

## Especificaciones del Diseño

La base de datos diseñada contempla cuatro tablas principales con sus respectivas relaciones:

* Proveedor: Almacena información de cada proveedor, incluyendo el nombre, dirección, ciudad, provincia y un código de proveedor único.

* Suministro: Relaciona los proveedores con las piezas suministradas, registrando la fecha, cantidad y el precio total del suministro. Es posible registrar múltiples suministros de una misma pieza por un proveedor en diferentes fechas.

* Pieza: Contiene los detalles de cada pieza como su código único, nombre, color, precio y la categoría a la que pertenece.

* Categoría: Define las distintas categorías de piezas con un nombre y un código de categoría único.

## Resultado

El resultado del proyecto se refleja en el modelo de la base de datos proporcionado, que ilustra las tablas, campos, tipos de datos y las relaciones entre las tablas. El modelo fue cuidadosamente creado para asegurar la normalización y la eficiencia en el almacenamiento y recuperación de datos.

## Herramientas y Recursos Utilizados

* Lucidchart: Una herramienta en línea para crear y compartir diagramas, mapas mentales y organigramas, con funciones de colaboración en tiempo real
* PowerPoint: Parte de Microsoft Office, es una aplicación para diseñar presentaciones con diapositivas, incorporando texto, imágenes y animaciones.




## Contribuidores
Este proyecto ha sido elaborado por:

  <li>Vanessa Patiño Del Hoyo
  <li>Alvaro Alonso Berenguer
  <li>Miguel Montuenga Díaz