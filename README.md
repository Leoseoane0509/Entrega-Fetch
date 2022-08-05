# Entrega-Operadores-Librerias

# OPERADORES AVANZADOS
En esta entrega lo que hice fue agregar algunos operadores avanzados: 
1 - Operador ++ (línea 345) para sumarle uno a la cantidad que ya tenía del producto en el carrito
2 - Operador -- (línea 356) para restarle uno a la cantidad que ya tenía del producto en el carrito
3 - Ejemplo uno de spread operator (línea 273) para hacer una copia del producto que cree en el carrito de compras
4 - Ejemplo dos de spread operator (línea 363) para hacer una copia del producto que cree en el carrito de compras
5 - Ejemplo uno de operador ternario (línea 53) para chequear si el usuario paso algun valor en la variable name, y si  lo hizo, saludarlo con una ventana de alerta por su nombre
6 - Ejemplo dos de operador ternario (línea 135) para chequear si la hora es mayor a 12, en cuyo caso le agrego PM, y si es menor a 12, le agrego AM 
7 - Ejemplo tres de operador ternario (línea 137) para chequear si la hora es menor a 10, en cuyo caso le agrego un 0 adelante; sino, la dejo sin modificar
8 - Ejemplo tres de operador ternario (línea 139) para chequear si los minutos son menores a 10, en cuyo caso les agrego un 0 adelante; sino, los dejo sin modificar
9 - Ejemplo tres de operador ternario (línea 141) para chequear si los segundos son menores a 10, en cuyo caso les agrego un 0 adelante; sino, los dejo sin modificar


# LIBRERIAS
En esta entrega lo que hice fue utilizar dos librerias: sweet alert y toastify
1 - Sweet Alert la use para crear dos ventanas: una que aparece al principio de todo(cada vez que se refresque el navegador)y que le pregunta al usuario su nombre, y luego lo saluda; y después la use para crear una ventana cada vez que el usuario haga click en el botón enviar del formulario, para hacerle saber que su mensaje se envió correctamente
2 - Toastify la use para crear cuatro notificaciones: una cuando el usuario agregue un producto al carrito clickeando en el botón "add to cart"; otra cuando el usuario agregue un item más del producto en el carrito, clickeando en el signo +; otra cuando el usuario quite un item del carrito, clickeando en el signo -; y otra cuando el usuario decida clickear el botón "empty cart" para vaciar el carrito 

# ASINCRONÍA 
Para la clase de asincronía lo que hice fue agregar un setTimeout con un tiempo de 1 segundo, para que cada un segundo se vaya actualizando en el navegador la función clock(), que contiene el reloj digital
