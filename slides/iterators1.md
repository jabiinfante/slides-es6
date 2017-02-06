# Iterable
El protocolo Iterable define el comportamiento de iteración de ciertos Objetos Javascript.

Por defecto: String, Array, TypedArray, Map y Set.

Un Objeto será iterable si implementa la clave **Data[Symbol.iterator]**
<code><pre>
let str = "Hola";
console.log(typeof str[Symbol.iterator]); //function
</pre></code>

> Un objeto *Iterator* será *Iterable*; pero *Iterable* no tiene porqué ser *Iterator*.
