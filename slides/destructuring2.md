# Destructuring -- objetos

Permite asignaciones directamente desde OBJETOS

<pre><code>
let coords = [45,67,100];
// asignación desde array
let [x,y] = coords;
console.log(x); //45
let z = 0;
// asignación desde array literal
[x,y,z] = [y,x]
console.log(x); //67
// valor no definido, asigna 'undefined'
console.log(z); //undefined
// asignación omitiendo valores
[,,z] = coords;
console.log(z); //100
</code></pre>