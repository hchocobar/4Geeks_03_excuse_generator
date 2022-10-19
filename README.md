# Generador de Excusas en Javascript

## The Excuse Generator

El generador de excusas toma 20 líneas de código, es super simple de entender y es el primer proyecto perfecto para cualquier desarrollador principiante.

Es un proyecto que usa muy poco de Javascript y que tiene una aplicación muy divertida. No más de 20 líneas de código.

## Instrucciones

Crea un sitio web pequeño que genere una excusa cada vez que se presione se refresque el browser.

Crea un index.html con una excusa codificada, no js, solo una excusa en HTML puro y simple.
    La excusa debe estar dentro de una etiqueta HTML que tenga un ID asignado, por ejemplo:

```html
    <p id="excuse">My dog eat my homework</p>
```

Usando javascript, crea una función que genere y devuelva una excusa aleatoria con la siguiente estructura:

```javascript
let who = ['the dog','my granma','his turtle','my bird'];
let what = ['eat','pissed','crushed','broked'];
let when = ['before the class','right in time','when I finished','during my lunch','while I was praying'];
```

Para crear una excusa consistente, tienes que concatenar un elemento de cada array o arreglo en el orden correcto.
Llama a esa función onLoad y establezca la excusa en el innerHTML del elemento HTML #excuse.

## Tecnologías

HTML, CSS3, Javascript.

## Fundamentos

Este ejercicio cubre los siguientes fundamentos:

* Utilizar archivos Javascript externos en tu proyecto.
* Cómo trabajar con arreglos.
* Generar números al azar.
* Concatenar strings (cadenas).
* Utilizar funciones (al menos un poco).
* Trabajar con eventos (al menos un poco).
