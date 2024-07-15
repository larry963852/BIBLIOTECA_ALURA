# Literalura

Literalura es una aplicación Java/Spring Boot para amantes de los libros. Esta aplicación permite buscar libros, listar libros registrados, listar autores, y muchas otras funcionalidades relacionadas con la lectura y organización de libros.

## Funcionalidades

- **Buscar libros por título:** Consulta la API de Gutendex para buscar libros por título.
- **Listar libros registrados:** Muestra todos los libros registrados en la base de datos.
- **Listar autores registrados:** Muestra todos los autores de los libros registrados.
- **Listar autores vivos en un año determinado:** Lista autores que estaban vivos en un año especificado.
- **Listar autores nacidos en un año determinado:** Lista autores que nacieron en un año especificado.
- **Listar autores por año de fallecimiento:** Lista autores que murieron en un año especificado.
- **Listar libros en un idioma determinado:** Lista libros registrados en la base de datos en un idioma especificado.
- **Cerrar la aplicación:** Finaliza el programa.

## Tecnologías Utilizadas

- Java 17
- Spring Boot 2.7
- Hibernate
- PostgreSQL
- Gutendex API
- Maven

## Configuración del Proyecto

### Prerrequisitos

- Java 17 o superior
- Maven
- PostgreSQL

## Uso

Al iniciar la aplicación, se mostrará el menú principal con las opciones disponibles. Sigue las instrucciones en pantalla para navegar por las funcionalidades.

### Ejemplos de Uso

- **Buscar libros por título:**
  1. Digita `1` y presiona Enter.
  2. Ingresa el título del libro que deseas buscar.
  3. La aplicación consultará la API de Gutendex y mostrará los resultados encontrados.

- **Listar libros registrados:**
  1. Digita `2` y presiona Enter.
  2. La aplicación listará todos los libros registrados en la base de datos.

- **Listar autores registrados:**
  1. Digita `3` y presiona Enter.
  2. La aplicación listará todos los autores de los libros registrados.

- **Listar autores vivos en un año determinado:**
  1. Digita `4` y presiona Enter.
  2. Ingresa el año deseado.
  3. La aplicación listará los autores que estaban vivos en ese año.

- **Listar autores nacidos en un año determinado:**
  1. Digita `5` y presiona Enter.
  2. Ingresa el año deseado.
  3. La aplicación listará los autores que nacieron en ese año.

- **Listar autores por año de fallecimiento:**
  1. Digita `6` y presiona Enter.
  2. Ingresa el año deseado.
  3. La aplicación listará los autores que murieron en ese año.

- **Listar libros en un idioma determinado:**
  1. Digita `7` y presiona Enter.
  2. Ingresa el código del idioma deseado (por ejemplo, `en` para inglés, `es` para español).
  3. La aplicación listará todos los libros registrados en ese idioma.

- **Cerrar la aplicación:**
  1. Digita `0` y presiona Enter.
  2. La aplicación se cerrará.
