# Spread

Es útil para extender objetos:

<pre><code>
var a = {
    valor1: 1,
    valor2: 2,
    valor3: 3
};
var b = {
    ...a,
    valor22: 22
};
console.log(a); // Object {valor1: 1, valor2: 2, valor3: 3}
console.log(b); // Object {valor1: 1, valor2: 22, valor3: 3}
</pre></code>
