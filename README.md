# Event Listeners

Nos permiten agregar funciones a eventos en el DOM, la sintaxis puede ser `elemento.addEventListener("click", funcion);`.

Los event listeners que existen son:

- click.
- scroll.
- mouseenter.
- mouseleave.


# Selección de elementos

Se pueden usar las siguientes opciones:

- **querySelector:** Permite seleccionar un elemento usando la sintaxis de CSS, es decir . para las clases, # para los ids o si queremos seleccionar un tag también podemos hacerlo.
- **querySelectorAll:** Permite hacer lo mismo que el selector `querySelector` con la diferencia de que el primero sólo trae la primer coincidencia, y este crea un arreglo de todos los elementos encontrados en el DOM que coinciden con nuestro parámetro.
- **getElementById:** Permite obtener un elemento por su id.


# Cambiar estilo de elementos

Se puede hacer uso de la propiedad `.style`, por ejemplo si deseamos cambiar el ancho podemos escribir lo siguiente: `progress.style.width = ((actives.length - 1) / (circles.length - 1)) * 100 + "%";`.


# Modificar lista de clases

Si tenemos una variable div y deseamos agregar una clase a dicho elemento podemos escribir la línea de código `div.classList.add("clase");` y si deseamos eliminar la clase podemos escribir `div.classList.remove("clase");`.

Por otra parte, en algunos casos podríamos querer que agregue y elimine la clase dependiendo de si la tiene o no, y para no tener que controlar esto podemos hacer uso del `.toggle`, por ejemplo `div.classList.toggle("clase");`.


# Cambiar el texto de un elemento

Existe la propiedad `.innerText` que nos permite realizar esto, la sintaxis es `texto.innerText = "Nuevo texto";`.


# Obtener propiedades de elementos/window

- **Posición en Y:** `window.innerHeight`.
- **Posición en X:** `window.innerWidth`.
- **Tamaño y posición del elemento:** `elemento.getBoundingClientRect()`.