# Iterable / Iterator
Un String, Iterable, no es un Iterator
<code><pre>
let str = "Hola";
console.log(str.next()); // TypeError: str.next is not a function
</pre></code>

Su Symbol.Iterator, si que implementa Iterator
<code><pre>
let str = "Hola";
let iterStr = str[Symbol.iterator] ();
console.log(iterStr.next()); // { value: 'H', done: false }
</pre></code>
