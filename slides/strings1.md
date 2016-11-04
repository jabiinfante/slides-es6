# Strings Iterables

Pueden usarse con un for-of
(que iterará entre caracteres)

```
let str = 'Hola';
for (let c of str) {
  console.log(c); //H - o - l - a
}
```

Ó con _spread_, para convertir los caracteres a array:
```
let str = 'Hola';
let arr = [...str];
console.log(arr); // ["H", "o", "l", "a"]
```

**UTF-16 safe**