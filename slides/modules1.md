# export
Un módulo es un fichero JS, que contiene cierta lógica, y que exporta (expone), uno o varios objetos o variables definidos en su propio contexto.

Estas exportaciones pueden ser especificadas por nombre:
<pre><code>
#module1.js
const nombre = 'mi modulo';
export {nombre};
function sum(...numbers) {
    var total = 0;
    numbers.map(x=> total+=x);
    return total;
}
function multiply(...numbers) {
    var total = 1;
    numbers.map(x=> total*=x);
    return total;
}
export {sum,multiply}
</code></pre>
