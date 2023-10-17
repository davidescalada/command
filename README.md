# command
Patrón seleccionado: Command

Descripción del proyecto: Se trata sobre dos botones que contienen el comportamiento de generar un efecto de fade al otro botón e ir a una escena nueva mediante la acción del clic. La idea en si es recibir comandos asincronicos , que se almacenaran en una lista y se ejecutaran uno atrás del otro, es decir cuando termine la ejecución del comando actual. 

Cuál es la problemática con la que nos encontraríamos en el ejercicio si no aplicaramos el patrón?
R: El problema seria que si necesitamos aplicar este efecto de fade en otros objetos o cargar escenas, vamos a tener que codear nuevamente el comportamiento.

Por qué el patrón soluciona esa problemática? de que forma lo hace?
R: Porque se puede reutilizar los comportamientos para aplicar estas acciones sobre cualquier otro objeto, sin necesidad de modificar en gran medida del código. Solo necesitamos cargar los objetos que deseamos dentro de las dependencias desde el motor.

Que ventajas y desventajas tiene el patrón seleccionado?
R: Por un lado cada objeto mantienen una conexion pero la accion final la lleva a cabo el comando en particular, lo anterior solamente es una manera de administrar la ejecución del problema. Al poder abstraerlo de cierta manera, podemos llegar a configurar los comportamientos de muchos objetos sin necesidad de entrar en modificación de código, solo teniendo un scrip quien controle dicha configuración (por ej si tenemos un juego con distintos tipos de dificultades).  Por ultimo una de las desventajas que puedo ver sea la dificultad de abstraer los comportamientos a tal punto para que funcione el patrón. 

