# Set
<code><pre>
let set = new Set();
set.add('val1');
let objectValue = { key: 2};
set.add(objectValue);
console.log(set.size); // 2
console.log(set.has(objectValue)); // true
set.forEach(function(val) {
  console.log(val);
  // val1
  // { key: 2 }
});
set.clear();
console.log(set.size); // 0
</pre></code>
