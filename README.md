¡Hola!

Continuando con el proceso, la prueba para pasar a la siguiente etapa consiste en hacer un buscador de música usando la data de `Spotify` a través de su API, puntualmente queremos que desarrolles las siguientes características:

- Listar la información de un album, artista o canción
- Posibilidad de escuchar un preview de la canción.
- Cada canción que fue escuchada, debe quedar en un historial del usuario para luego volver a consultarla. `Evaluaremos tu criterio de como resolver este problema.`

### Ejercicio extra

Además necesitamos que resuelvas estos pequeños ejercicios, no debería tomar más de 15min.

#### Ejercicio 1

Escribir una función que reciba una matriz de numéricos como parámetro, y devuelva otra función que espere como parámetro una función que pueda hacer algo con la suma de la matriz original de enteros. Los números pares > 20 deben ser tratados como un 20.

La solución y ejemplo de código debe ser algo más o menos así: `sum([1,2,3])(result => console.log(result))`

#### Ejercicio 2

Escribe un componente en React llamado `ListNicknames` que acepte una lista de nombres como propiedad e imprima los nick orden Ascendente o descendente según una propiedad usando una lista `<ul>`
Ejemplo:

```js
<ListNicknames
  names={["Triviño TI", "Homer Dev", " ", " Ragnar Front", "Loki UX"]}
  order="ASC"
/>
```

### La pauta

- La aplicación debe ser desarrollada usando Reactjs 16.14+
- Manejar estados globalmente con Redux
- La interfaz de la aplicación no es relevante, pero puntos extras si le das un poco de color y estilo.
- El buscador debe soportar multi criterios, es decir, poder buscar por álbum, artista o título, incluso de manera combinada (tal como funciona el de Spotify).
- El campo de búsqueda debe incluir validación ¿Cuál? `Evaluaremos tu criterio`.
- El historial de búsqueda debe ser persistente.

### Los criterios de evaluación serán

- Implementación
- Convención de código
- Validaciones
- Orden
- Funcionalidad de la aplicación
- Suma puntos el uso de documentación en los componentes o funciones desarrolladas
- Suma puntos extras el uso de Typescript y/o tests con `react-testing-library` y/o `Cypress`.
- La entrega de la prueba un repositorio público de Github/GitLab dónde podamos ver el código y su evolución, además deberás proveernos una URL para probar su funcionalidad.

Si tienes alguna pregunta, no dudes en escribirnos.

- victor@eclass.com
- sebastian@eclass.com

¡Saludos!
