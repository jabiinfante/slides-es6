# Map
<code><pre>
let map = new Map();
map.set(0, 'val1');
map.set({ key: 2 }, {a: 'test'});
console.log(map.size); // 2
map.forEach(function(val,key) {
  console.log(key , val);
  // 0 'val1'
  // { key: 2 } { a: 'test' }
});
map.clear();
console.log(map.size); // 0
</pre></code>
