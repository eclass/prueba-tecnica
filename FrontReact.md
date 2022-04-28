¡Hola!

Continuando con el proceso, la prueba para pasar a la siguiente etapa consiste en hacer un buscador de personajes de la serie `the Rick and Morty` a través de esta [GraphQl API](https://rickandmortyapi.com/graphql), puntualmente queremos que desarrolles las siguientes características:

- Listar personajes que aparecen en la serie (imagen, nombre)
- Al cliquear sobre uno de ellos enviar a página con su información detallada (La que creas conveniente)
- Poder guardar como favorito alguno de los personajes
- Vista con los favoritos que guardaste

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
- Conectarse con la api a través de Apollo Client
- Manejar estados globalmente con Redux
- La interfaz de la aplicación no es relevante, pero puntos extras si le das un poco de color y estilo.
- El historial de favoritos debe ser persistente `update 01 diciembre`

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
