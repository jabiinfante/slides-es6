# Generators
## ejemplo
<code><pre>
for (let val of gen) {
  console.log(val); // 1 // 2 // 3
}
</pre></code>

<code><pre>
console.log(gen.next()); // {value: 1, done: false}
console.log(gen.next()); // {value: 2, done: false}
console.log(gen.next()); // {value: 3, done: false}
console.log(gen.next()); // {value: undefined, done: true}
</pre></code>
