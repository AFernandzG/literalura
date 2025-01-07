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
```plaintext
---- AUTORES REGISTRADOS ----
Autor: Dickens, Charles | Fecha de nacimiento: 1812 - Fecha de fallecimiento: 1870
Libros:
- Great Expectations (Idioma: en, Descargas: 22840)
--------------------------------------------------
Autor: Austen, Jane | Fecha de nacimiento: 1775 - Fecha de fallecimiento: 1817
Libros:
- Pride and Prejudice (Idioma: en, Descargas: 56305)
--------------------------------------------------
Autor: Melville, Herman | Fecha de nacimiento: 1819 - Fecha de fallecimiento: 1891
Libros:
- Moby Dick; Or, The Whale (Idioma: en, Descargas: 72786)
--------------------------------------------------
```
### 📅 Listar autores vivos en un determinado año
```plaintext
---- AUTORES VIVOS POR AÑO ----
Ingrese el año para consultar: 
1850
Autores vivos en 1850:
- Dickens, Charles (Nacimiento: 1812 | Fallecimiento: 1870)
  * Libro: Great Expectations
- Melville, Herman (Nacimiento: 1819 | Fallecimiento: 1891)
  * Libro: Moby Dick; Or, The Whale
- Eliot, George (Nacimiento: 1819 | Fallecimiento: 1880)
  * Libro: Middlemarch
- Hawthorne, Nathaniel (Nacimiento: 1804 | Fallecimiento: 1864)
  * Libro: The Scarlet Letter
- Alcott, Louisa May (Nacimiento: 1832 | Fallecimiento: 1888)
  * Libro: Little Women; Or, Meg, Jo, Beth, and Amy
- Hugo, Victor (Nacimiento: 1802 | Fallecimiento: 1885)
  * Libro: Les Misérables
  * Libro: Notre-Dame de Paris - Tome 1
```
### 🌐 Listar libros por idioma
```plaintext
---- LIBROS POR IDIOMA ----
Idiomas disponibles: ES (Español), EN (Inglés), FR (Francés), PT (Portugués)
Ingrese el código del idioma: es

 -> Libros en Español:
- Don Quijote (Autor: Cervantes Saavedra, Miguel de)
- Noli me tángere: Novela Tagala, Edición completa con notas de R. Sempau (Autor: Rizal, José)
- Mi Ultimo Adiós (Autor: Rizal, José)
- La isla del tesoro (Autor: Stevenson, Robert Louis)
```
## Instalación 🚀

1. Clona este repositorio:
    ```bash
    git clone https://github.com/AFernandzG/literalura.git
    ```
2. Asegúrate de tener Java y Maven instalados en tu sistema.
3. Ejecuta el proyecto:
```bash
mvn spring-boot:run
```
### 📋 Requisitos
- Java 11 o superior
- Maven
- Biblioteca Gson para serializar y deserializar datos JSON.

## 🤝 Contribución
Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

Haz un fork del proyecto.

Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).

Realiza tus cambios y haz commit (`git commit -am 'Agregar nueva funcionalidad'`).

Sube tus cambios (`git push origin feature/nueva-funcionalidad`).

Abre un Pull Request.

### 📝 Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más información.

¡Gracias por visitar nuestro proyecto y esperamos que te resulte útil! 🙌
