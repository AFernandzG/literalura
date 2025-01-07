# 📚 Proyecto de Gestión de Libros y Autores
<p align="left">
   <img src="https://img.shields.io/github/stars/AFernandzG?style=social">
   </p>

¡Bienvenido/a al Proyecto de Gestión de Libros y Autores! 🎉 Este proyecto está diseñado para ayudarte a gestionar libros y autores utilizando Java y Spring Boot. Aquí encontrarás todo lo que necesitas para comenzar a usar este sistema y sacarle el máximo provecho.

## ✨ Características

- **🔍 Buscar libro por título:** Busca un libro por su título, primero en la base de datos local y luego en una API externa si no se encuentra.
- **📚 Listar libros registrados:** Muestra todos los libros registrados en la base de datos.
- **📝 Listar autores registrados:** Muestra todos los autores registrados junto con los libros asociados.
- **📅 Listar autores vivos en un determinado año:** Muestra autores que estaban vivos en un año especificado.
- **🌐 Listar libros por idioma:** Muestra libros filtrados por idioma.

## 💡 Ejemplos de Uso

### 🔍 Buscar libro por título

```plaintext
---- BÚSCAR LIBRO ----
Escriba el título del libro: potter
Buscando en la API externa...
Guardando nuevo autor: Wedgwood, Josiah C. (Josiah Clement)

Libro guardado exitosamente:
<---- LIBRO ---->
titulo: Staffordshire pottery and its history
Autor: Wedgwood, Josiah C. (Josiah Clement)
idioma: en
Numero de Descargas: 816
<*************************************>
```
### 📚 Listar libros registrados
```plaintext
---- LIBROS REGISTRADOS ----
<---- LIBRO ---->
titulo: Great Expectations
Autor: Dickens, Charles
idioma: en
Numero de Descargas: 22840
<*************************************>

<---- LIBRO ---->
titulo: Pride and Prejudice
Autor: Austen, Jane
idioma: en
Numero de Descargas: 56305
<*************************************>
```
### 📝 Listar autores registrados
