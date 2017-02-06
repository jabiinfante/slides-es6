# Iterable / Iterator
Cualquier objeto no será Iterable:
<code><pre>
let obj = {
  myColection : [1,2,3,4],
}
for(let item of obj) {
  console.log(item); //TypeError: obj[Symbol.iterator] is not a function
}
</pre></code>

Pero puede serlo implementando Symbol.Iterator:
<code><pre>
let obj = {
  myColection : [1,2,3,4]
}
obj[Symbol.iterator] = () => obj.myColection[Symbol.iterator] ();
for(let item of obj) {
  console.log(item); //1 //2 //3 //4
}
</pre></code>
