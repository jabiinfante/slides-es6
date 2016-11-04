# Rest

Existe la posibilidad de recibir los parámetros de una función en un array

<strike>var numbers = Array.prototype.slice.call(arguments)</strike>

<pre><code>
function mult(...numbers) {
    var total = 1;
    numbers.map(x=> total*=x);
    return total;
}

console.log(mult(2,2,2)); // 8
console.log(mult(5,8)); // 40

</code></pre>