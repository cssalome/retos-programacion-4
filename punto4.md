## CiCLOS

- ¿Qué es un ciclo?

  - Los bucles o ciclos son sentencia sque se utilizan para ejecutar una o varias instrucciones de forma repetitiva cuando sea necesario

- ¿Qué tipos de ciclos existen en JavaScript?

  - Existen tres tipos de bucles principales pero dentro de estos también existen sus propias ramas como veremos a continuación: for(for in, for of, for-each), while, do while.

- ¿Qué es un ciclo infinito y por qué es un problema?

  - Existen 3 ciclos el while, el for ,y el do while

- ¿Puedo mezclar ciclos y condicionales?
  - Si

## Replica el comportamiento de los siguientes ciclos for utilizando ciclos while:

for (let i = 0; i < 5; i++) {
console.log("El valor de i es: " + i);
}
for (let i = 10; i >= 2; i--) {
console.log("El valor de i es: " + i);
}

`let i = 0 while(i < 5){ console.log("El valor de i es: " + i); i++ } let= j = 10 while(j>=2){ console.log("El valor de i es: " + i); i--}`

## Escribe un código en JavaScript que le pregunte a los usuarios cuánto es 2 + 2. Si responden bien, mostramos un mensaje de felicitaciones, pero si responden mal, volvemos a empezar.

while (esIncorrecto) {
const resp = Number(prompt("¿Cuento es 2 + 2?"));
if (resp === 4) {
esIncorrecto === false;
}
}

Pista: puedes usar la función prompt de JavaScript.
