# Valores por defecto

Es posible indicar el valor por defecto a los argumentos de las funciones.
<strike><code>arg = arg || _valor_por_defecto;</code></strike>

<pre><code>
function mult(a,b=1,c=1,d) {
    return a*b*c*d;
}

console.log(mult(2,2,2,2)); // 16
console.log(mult(2,undefined,undefined,2)); // 4
console.log(mult(2,undefined,undefined)); // NaN

</code></pre>


