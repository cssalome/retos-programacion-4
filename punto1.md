## VARIABLES Y OPERACIONES

## ¿Qué es una variable y para qué sirve?

- Una variable es una forma para almacenar o guardar un valor en la memoria RAM para
  reutilizarlas, calcularlas, etc.

## ¿Cuál es la diferencia entre declarar e inicializar una variable?

- **Declarar** es darle un nombre a una variable
  mientras que **inicializar** es darle un valor

## ¿Cuál es la diferencia entre sumar números y concatenar strings?

- Una suma solo se puede hacer con variables tipo number. En cambio
  concatenar es unir string con algun otro tipo de balor.

## ¿Qué operador me permite sumar o concatenar?

- El operador: **+**

## Determina el nombre y tipo de dato para almacenar en variables la siguiente información:

Nombre `const nombre = 'Carla'`
Apellido `const apellido = 'Serrano'`
Nombre de usuario `const nomUsuario = 'SCSalome'`
Edad `let edad = 20 `
Correo electrónico `let email = 'c.salome.serrano@gmail.com'`
Mayor de edad `let mayorEd = true`
Dinero ahorrado `let ahorros = 13000`
Deudas `let deudas = 0`

## Traduce a código JavaScript las variables del ejemplo anterior y deja tu código en un archivo nuevo.

`const persona = {nombre:'Carla', apellido:'Serrano', nomUsuario:'SCSalome', edad : 20, email:'c.salome.serrano@gmail.com' , mayorEd : true, ahorros : 13000, deudas : 0}`

## Calcula e imprime las siguientes variables a partir de las variables del ejemplo anterior:

Nombre completo (nombre y apellido)
`const nomCompleto = persona.nombre + ' ' +persona.apellido`
Dinero real (dinero ahorrado menos deudas)
`const dineroReal = 'Dinero real:' + ' ' + persona.ahorros - deudas`
