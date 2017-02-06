# Strings

ES6 introduce nuevos métodos para Strings, así como funcionalidades extra muy *interesantes*

## Templates \`Plantillas\`

<pre><code>
let name = 'Luis Felipe';
let likes = 'docker';

let saludo = `Hola ${name}. Te gusta ${likes}.`;
console.log(saludo); // Hola Luis Felipe. Te gusta docker.
</code></pre>

## Soporte multilínea (para plantillas!)
<pre><code>
let frase = `Hola
¿qué tal?
¿bien?`;

console.log(frase); // Hola\n¿qué tal?\n¿bien?
</code></pre>

