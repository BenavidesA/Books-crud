# Sistema de Gestión de Biblioteca

Este es un programa en C para gestionar una pequeña biblioteca. Permite registrar libros, mostrar los libros registrados, buscar un libro por su ID o título, cambiar el estado de un libro (de "Disponible" a "Prestado" o viceversa) y eliminar un libro de la lista.

## Funcionalidades

### 1. **Registrar Libro**
   Permite ingresar los datos de un libro, incluyendo su ID, título, autor, año de publicación y estado (inicialmente se configura como "Disponible"). Se validan entradas para asegurarse de que no se ingresen más de 20 libros ni IDs duplicados.

### 2. **Mostrar Libros**
   Muestra todos los libros registrados, incluyendo su ID, título, autor, año y estado. Solo se muestran los libros que han sido correctamente registrados.

### 3. **Buscar Libro por ID**
   Permite buscar un libro por su ID y muestra los detalles del libro encontrado, incluyendo su título, autor, año de publicación y estado.

### 4. **Buscar Libro por Título**
   Permite buscar un libro por su título y muestra los detalles del libro encontrado.

### 5. **Cambiar Estado de un Libro**
   Cambia el estado de un libro entre "Disponible" y "Prestado". Esto es útil para llevar un registro de los libros que han sido prestados.

### 6. **Eliminar un Libro**
   Permite eliminar un libro de la lista de libros registrados. El libro se elimina buscando por su título y desplazando los elementos restantes para llenar el espacio vacío.

### 7. **Salir**
   Finaliza la ejecución del programa.

## Estructura de Datos

El programa maneja una estructura llamada `Libro` que contiene los siguientes campos:

- **ID**: Un identificador único para cada libro (entero).
- **Título**: El título del libro (cadena de texto).
- **Autor**: El autor del libro (cadena de texto).
- **Año**: El año de publicación del libro (entero).
- **Estado**: El estado del libro, que puede ser "Disponible" o "Prestado" (cadena de texto).

## Requisitos

Este programa está escrito en C y utiliza las siguientes librerías estándar:

- `stdio.h`
- `string.h`

## Limitaciones
El programa está limitado a un máximo de 20 libros.
Solo se permiten IDs únicos para cada libro, y el programa valida la entrada para evitar duplicados.

