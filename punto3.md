## CONDICIONALES

## ¿Qué es una condicional?

- Los condicionales es una forma de controlar el flujo de ejecucion
  de mi codigo. Por el dado verdadero y el falso.

## ¿Qué tipos de condicionales existen en JavaScript y cuáles son sus diferencias?

Existen 4 tipos: if else, else if, switch e if ternario.

## ¿Puedo combinar funciones y condicionales?

si

## Replica el comportamiento del siguiente código que usa la sentencia switch utilizando if, else y else if:

const tipoDeSuscripcion = "Basic";

switch (tipoDeSuscripcion) {
case "Free":
console.log("Solo puedes tomar los cursos gratis");
break;
case "Basic":
console.log("Puedes tomar casi todos los cursos durante un mes");
break;
case "Expert":
console.log("Puedes tomar casi todos los cursos durante un año");
break;
case "ExpertPlus":
console.log("Tú y alguien más pueden tomar TODOS los cursos durante un año");
break;
}

`if (tipoDeSuscripcion === 'Free'){ console.log("Solo puedes tomar los cursos gratis"); } else if (tipoDeSuscripcion === 'Basic') { console.log("Puedes tomar casi todos los cursos durante un mes") } else if (tipoDeSuscripcion === 'Expert') { console.log("Puedes tomar casi todos los cursos durante un año") } else if (tipoDeSuscripcion === 'ExpertPlus'){ console.log("Tú y alguien más pueden tomar TODOS los cursos durante un año") }`

## Replica el comportamiento de tu condicional anterior con if, else y else if, pero ahora solo con if (sin else ni else if).

`if (tipoDeSuscripcion === 'Free') console.log("Solo puedes tomar los cursos gratis");`
`if (tipoDeSuscripcion === 'Basic') console.log("Puedes tomar casi todos los cursos durante un mes")`

## Bonus: si ya eres una experta o experto en el lenguaje, te desafío a comentar cómo replicar este comportamiento con arrays y un solo condicional.

`const subs = ['Free', 'Basic', 'Expert', 'ExpertPlus']`
`const mensaje = ['m1', 'm2', 'm3', 'm4' ]`
`const pos = sub.indexOf(posicion de suscripcion)`

`if (sub){`
` console.log(mensaje[pos])`
}`
