# Calculadora Eduardo Mendez
# Explicación de Código JavaScript


### 1. `document.querySelector(".display");`

Esta línea de código busca en el documento HTML un elemento que tenga la clase "display".

### 2. `const buttons = document.querySelectorAll("button");`

Esta línea de código busca en el documento HTML todos los elementos que sean botones (`<button>`).

### 3. `buttonText = button.textContent;`

Esta línea de código obtiene el texto contenido dentro del botón y lo asigna a la variable `buttonText`.

### 4. `buttons.forEach((button) => { ... }`

Esta línea de código itera sobre todos los elementos de la lista `buttons` y ejecuta la función especificada para cada uno de ellos.

### 5. `button.addEventListener("click", () => { } )`

Esta línea de código añade un "event listener" al botón que espera el evento de clic (`click`).

