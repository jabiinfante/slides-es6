# WeakMap
<code><pre>
let wmap = new WeakMap();
let k1 = { key: 2 };
wmap.set(new Date(), 'val1');
wmap.set(k1, {a: 'test'});
console.log(wmap.has(k1)); // true
console.log(wmap.has({key: 2})); // false (reference!)
console.log(wmap.get(k1)); // { a: 'test' }
</pre></code>
