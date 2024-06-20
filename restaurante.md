# Prueba sofain 20-06-2024

## Reglas

1. La prueba debe realizarse usando laravel.
2. No se permite el uso de inteligencia artificial durante la prueba.
3. Se permite el uso de cualquier recurso de internet (Excluyendo ia).
4. Tiempo de la prueba, 4 horas.
5. Se dan puntos dependiendo de la cantidad de requisitos cumplidos.
6. Al terminar el reto debe ser subido a un repositorio de github para su revisión.

## Reto

Un cliente es dueño de un restaurante y quiere hacer mas comodo para los clientes el hacer sus pedidos, para esto nos pide una aplicación con los siguientes requisitos.

1. El sistema debe contar con un menu.
2. Los clientes deben poder crear ordenes.
3. Cada orden debe ir asociada a una mesa.

### Administración

1. Para acceder al panel de administracion se debe iniciar sesión.
2. Se deben poder agregar categorias al menu(crud):
   - Cada categoria debe tener un nombre y un color.
3. Se deben poder agregar platos a cada categoria(crud):
   - Cada plato tiene un nombre, una descripción y un precio.
   - Cada plato pertenece a una sola categoria.
4. Se deben poder crear mesas:
    - Cada mesa debe tener su numero y capacidad(4 personas, 2 personas , etc ...).
5. Se deben poder visualizar las ordenes y marcalas como completas.

### Usuarios

1. Para acceder al menu y crear ordenes no es necesario iniciar sesión.
2. Deben poder ver el menu, donde el titulo de cada categoria este del color que la representa.
3. Se debe poder crear una orden:
    - Cada orden debe tener los platos asociados, estado de la orden, la mesa asociada a esa orden. 
