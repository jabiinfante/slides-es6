# WeakSet
<code><pre>
let wset = new WeakSet();
let objectValue = { key: 2 };
wset.add({key: 'val1'});
wset.add(objectValue);
console.log(wset.has(objectValue)); // true
console.log(wset.has({key: 2})); // false
</pre></code>
