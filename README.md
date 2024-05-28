<h1 style="text-align: center; border: 8px double black; background-color: white;"> Proyecto: Desafío Literalura </h1>

<h3>Descripción del proyecto</h3>

<p>Este proyecto usa La api de <a href="https://gutendex.com/">Gutendex</a> para realizar distintas consultas a la misma para traerlos los resultado de la misma a la consola y mosotrarlos al usuario, a la vez de que también es posible exportar algunos  los datos de la a una base de datos SQL (<em>se necesita configurar en el archivo</em> <strong>application.properties</strong> además de colocar en el archivo <strong>POM.xml</strong> el conector a la base de datos que se desee usar) que creará tablas en la base de datos indicada para guardar los datos que se deseen exportar de la api, usando tecnologías como:</p>

<ul>
    <li>Java 17: como lenguaje de programación principal</li>
    <li>Spring boot como framework y maven como gestor de dependencias</li>
    <li>Spring Data JPA</li>
    <li>Dependecia Jackson</li>
</ul>

<h2 style="text-align: center;">Funciones del programa</h2>
<ol>
    <li>Consultar datos de la API de un libro, introduciendo el título del mismo, trayendo los datos del mismo, como el título, una lista de autores, los idiomas en los que está disponible el libro etc</li>
    <li>Traee una lista de libros de la API de determinado autor, introduciendo en nombre del mismo en la consola</li>
    <li>Traer una lista de autores vivos desde la API en determinado año introduciendo el año en la consola</li>
    <li>Una lista de los libros que ya fueron consultados en la sesíon actual</li>
    <li>Buscar un libro para añadirlo a la base de datos local para ser conultado depués</li>
    <li>Mostrar una lista de los libros que se han añadido a la base de datos local</li>
    <li>Mostrar una lista de los libros que están disponibles en algún idioma (se muestra una lista de los idiomas en los que se han almacenado libros)</li>
    <li>Mostrar cuantos libros hay disponibles en cada idioma en la base de datos</li>
    <li>Una lista de autores almacenados en la base de datos, que hayan estado vivos en determinado año</li>
</ol>
