# ¿Çué es LiterAlura?
Es una aplicación de consola desarrollada en Java con Spring Boot y PostgreSQL para consultar libros de dominio público en varios idiomas. Desarrollada en Java con Spring Boot y PostgreSQL, se conecta a la API de Gutenberg para obtener y almacenar información de libros. Es parte del "Challenge One" del programa Alura Oracle Next Education.

## ¿Cómo funciona?
Se conecta a la API de Guntendex (https://gutendex.com/) para obtener información sobre libros de dominio público y almacenarla en una bdd PostgreSQL.

Al iniciar la aplicación, se muestra un menú con opciones para buscar libros, consultar libros guardados, consultar autores, consultar autores por año y consultar libros por idioma. Al buscar un libro, se obtiene la información de la API y se guarda en la base de datos. Las opciones de consulta permiten visualizar los datos almacenados. 

## ¿Cómo puedes utlizarlo?
1. Clona o descarga el proyecto
2. Inicia la carpeta del proyecto en tu editor de código
3. Configura tu archivo application.properties
4. Ejecuta la clase LiterAluraApplication

> Nota: 
> Debes contar con una instancia de postgresql ya que se creara la base de datos con las respectivas tablas al ejecutar la aplicacion
