# Spread (Propagación)

La funcionalidad _spread_, **extiende** los valores de un array (u objeto), como parámetros o como elementos de un mismo array (u objeto).

<pre><code>
function multiply(a,b,c,d=1) {
    return a &#42; b &#42; c &#42; d;
}
var a = [2,2,2];
var b = [3,3,3,3];
console.log(multiply(...a,2)); //16
console.log(multiply(...b)); //81
</pre></code>
