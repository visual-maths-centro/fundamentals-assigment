# Tarea 03. Fundfamentos de programación

### Instrucciones

Esta tarea se divide en 4 secciones: [Variables](#variables), [Condicionales](#condicionales), [Iteraciones](#iteraciones) y [Funciones](#funciones).

Cada una de estas secciones tiene ejercicios:

- Las respuestas de esta tarea se debe subir a Brightspace.
- Los ejercicios marcados como `js`, se deben responder con un enlace de [https://codesandbox.io/](CodeSandbox).
- En caso contrario, se debe subir un archivo o texto respondiendo lo que se pida.

En caso de tener alguna duda, no olvides enviar un correo.

## Variables

1. `js` Declara e inicializa todas las variables que consideres que se guardan en un contacto de una agenda telefónica.
2. `js` **Clon**. En base al [sandbox](https://codesandbox.io/s/clon-2mqek), haz un fork. Añade un clon de fulgencio que use las variables `fulgencio2X` y `fulgencio2Y` para posicionarse.

## Condicionales

1. `js` **Horizontal y Vertical**. Crea un sketch con dos elipses. Una recorre en horizontal, y cada vez que llega al ancho baja en la pantalla. Y la otra recorre el eje vertical, y cada vez que llega a la altura, se desplaza a la derecha.

<img src="verticalhorizontal.gif" alt="vertical" width="250" />

2. `js` **Bouncing Ball**. Crea un sketch con una elipse que rebota sin salirse del canvas. Es la misma que vimos en clase pero SIEMPRE debe verse completa. 

_Hint: guarda en una variable el tamaño de la elipse_.

<img src="bouncing.gif" alt="bouncing" width="250" />

3. `js` **Sides**. Crea un sketch con una elipse recorre los lados del canvas a una velocidad guardada en una variable.

_Hint: usa una variable entera para guardar en cuál lado estás_.

<img src="sides.gif" alt="sides" width="250" />

4. `js` **GrowButtons**. Crea un sketch con dos botones, uno agranda a un cuadro y el otro a una elipse. (En la muestra el click se ve con un circulo rojo).

<img src="buttons.gif" alt="twobuttons" width="250" />

## Iteraciones

1. `js` Usa la estrcutura `while` en los siguientes ejercicios:
   1. **Circles While**. Crea un sketch que dibuje el patrón:
   
   <img src="circles-while.png" alt="circles-while" width="250" />
   
   2. **Diagonals**. Crea un sketch que dibuje patrón:

   <img src="diagonals.png" alt="diagonals" width="250" />

2. Indica cuales de los siguientes ejemplos de `for` entran en loop infinito. En caso de ser falso, escribe cuales valores toman las variables.
   1. `for(let i = 0; i < 10; i--) {}`
   2. `for(let x = 1.0; x < 2000; x *= 2.0) {}`
   3. `for(let x = 10.0; x < 0; x = x / 2.0) {}`
   4. `for(let y = 20; y > 10; y++) {}`

3. `js` Repite los sketches del Ejercicio 1 pero usando la estructura `for`.
4. `js` **Curve**. Usa la estructura `for` para hacer el siguiente patrón:

<img src="curve.png" alt="curve" width="250" />

5. `js` **Mosaic**. Crea un sketch que dibuje un mosaico como el que sigue. Para cada cuadro del mosaico hay dos posibles dibujos. Decide cuál dibujar de forma aleatoria.

_Hint: usa_ `let coin = floor(random(2))` _para generar un número aleatorio que sea_ `0` _o_ `1`.
   
<img src="random-dfor.png" alt="random-dfor" width="250" />

6. `js` **Piramid**. Crea un sketch que dibuje el siguiente patrón:
   
<img src="piramid.png" alt="piramid" width="250" />

## Funciones

1. `js` **Vocales**. Crea un sketch que tenga 5 funciones, cada función debe dibujar una vocal. Cada vez que el usuario teclee esa vocal debe aparecer en la pantalla.
2. Sin ejecutar este código, di que se imprime en la consola cuando se ejecuta el siguiente código. Explica tu respuesta.

```js
function setup() {
  console.log( "a");
  function1();
  console.log( "b");
}

function draw() {
  console.log( "c");
  function2();
  console.log( "d");
  function1();
  noLoop();
}

function function1() {
  console.log( "e");
  console.log( "f");
}

function function2() {
  console.log( "g");
  function1();
  console.log( "h");
}
```
3. `js` **Area** Crea una función que calcule el area de un circulo en base a su radio.

Happy coding!

