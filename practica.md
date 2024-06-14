# Sistema de gestión de bibliotecas.

Se requiere un sistema que nos permita administrar muchas bibliotecas con una sola herramienta, para eso se presentan los siguientes requisitos:

## Pre requisitos.

Las bibliotecas deben ir vinculadas al usuario que las crea y este es el administrador de las bibliotecas que a creado. Por esta razon se debe contar con un sistema de registro y inicio de sesión.

## Administrador.

1. Debe permitir ingresar nuevas bibliotecas, con los siguientes datos:

   - Nombre: Debe ser obligatorio y contar con 5 a 30 caracteres.
   - Ubicación: Debe ser obligatoria y contar con 20 a 125 caracteres.
   - Descripción: No es obligatoria y debe tener maximo 500 caracteres.
   - Ningun campo debe guardar espacios ni al inicio ni al final.

2. Debe permitir registrar nuevos temas, con los siguientes datos:

   - Nombre: Debe ser obligatorio y contar con 5 a 30 caracteres.
   - Codigo de color: Es el codigo hexadesimal del color, no el nombre del color.

3. Debe permitir ingresar estanterias nuevas en una biblioteca:

   - Al ingresar a una biblioteca especifica debe tener la opcion de crear nueva estanteria.
   - La estanteria debe contar con los siguientes campos:
     - El tema al que pertenece la estanteria, debe ser obligatorio.
     - Codigo de la estanteria: Debe componerse de la primera letra del tema y un numero segun la cantidad de estanterias que tena la biblioteca a la que se encuentre asociada.

4. Debe permitir introducir nuevos autores, con los siguientes datos:

   - Nombre: Debe ser obligatorio y contar con 5 a 30 caracteres.
   - Biografia: Resumen de la biografia, debe tener maximo 500 caracteres.

5. Debe permitir registrar nuevos libros con los siguientes libros:

   - Nombre: Debe ser obligatorio y contar con 5 a 45 caracteres.
   - Fecha de publicación: debe ser obligatoria.
   - Autor del libro: obligatorio.

6. Debe permitir registrar nuevas copias de los libros, con los siguientes campos:
   - Libro al que pertenece la copia.
   - Numero de copia: obligatorio.
   - Estanteria donde se guarda la copia.

## Usuarios

1. Los usuarios deben permitir buscar bibliotecas, libros o autores que no hayan registrado ellos mismos.
2. Al ver las estanterias, estas deben verse segun el codigo de color del tema al que pertenecen.
3. Al buscar un libro debe mostrar las bibliotecas , el numero de copias que tenga cada biblioteca y la estanteria donde esten ubicadas.
4. Cuando un usuario entra a una biblioteca, debe mostrar las estanterias ordenadas segun el numero de libros que tenga cada 1.