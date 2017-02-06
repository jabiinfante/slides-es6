# Generators
## ejemplo
<code><pre>
function* elGenerador () {
  yield 1;
  yield 2;
  yield 3;
}
let gen = elGenerador(); // [object Generator]
</pre></code>

**gen** es un objeto de tipo Generator:
 - iterable
 - método **next()**
