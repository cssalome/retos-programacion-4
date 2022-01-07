## FUNCIONES

- ¿Qué es una función?

- Es un conjunto de insrucciones agrupadas en un bloque de codigo

- ¿Cuándo me sirve usar una función en mi código?

- Sirve para dividir tareas en diferentes funciones que unidas realizan una unica tarea

- ¿Cuál es la diferencia entre parámetros y argumentos de una función?

- Los **parametros** lon valores recibidos por la funcion inicializada
- Los **argumentos** son los valores enviados al llamar funcion

## Convierte el siguiente código en una función, pero, cambiando cuando sea necesario las variables constantes por parámetros y argumentos en una función:

const name = "Juan David";
const lastname = "Castro Gallego";
const completeName = name + lastname;
const nickname = "juandc";

console.log("Mi nombre es " + completeName + ", pero prefiero que me digas " + nickname + ".");

function presentacion(completeName, nickname) {
const saludo = `Mi nombre es ${completeName}, pero prefiero que me digas ${nickname}.`;
return saludo;
}

const nombres = presentacion(completeName, nickname);
