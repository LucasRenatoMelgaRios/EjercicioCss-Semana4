## Resumen General de Selectores en CSS

### Selectores Simples:

1. Selector de Etiqueta:
   - Uso: Aplica a todos los elementos de una etiqueta específica.
   - Ejemplo: `p { color: blue; }`

2. Selector de Clase:
   - Uso: Aplica a elementos con una clase específica.
   - Ejemplo: `.destacado { font-weight: bold; }`

3. Selector de ID:
   - Uso: Identifica un elemento único en la página.
   - Nota: No se recomienda para estilos, preferiblemente utilizado en JavaScript.
   - Ejemplo: `#encabezado { font-size: 24px; }`

4. Selector Universal:
   - Uso: Aplica a todos los elementos en la página.
   - Ejemplo: `* { margin: 0; padding: 0; }`

### Selectores Compuestos:

1. Selector Descendiente:
   - Uso: Aplica a un elemento o elementos que están niveles abajo, no necesariamente hijos directos.
   - Ejemplo: `div p { color: green; }`

2. Selector Hijo(s) Directo:
   - Uso: Selecciona al elemento o elementos hijos directos del padre, a un solo nivel de profundidad.
   - Ejemplo: `ul > li { list-style-type: square; }`

3. Selector Hermano Siguiente o Adyacente:
   - Uso: Selecciona al elemento que está al mismo nivel y siguiente del hermano.
   - Ejemplo: `h2 + p { font-style: italic; }`

4. Selector Hermanos Siguientes o Adyacentes:
   - Uso: Selecciona a los elementos que están al mismo nivel y siguientes del hermano.
   - Ejemplo: `h3 ~ p { color: red; }`

5. Selector Anidamiento:
   - Uso: Selecciona elementos anidados dentro de otros elementos.
   - Ejemplo: `.contenedor p { background-color: #ccc; }`

