# Nuevos métodos

## repeat(n)
```
console.log('penny '.repeat(3)); // 'penny penny penny ' 
```


## startsWith(str, starts = 0)
```
console.log('Irontec'.startsWith('Iron'));      // true
console.log('Irontec'.startsWith('tec', 4)); // true
```

## endsWith(str, ends = str.length)
```
console.log('Irontec'.endsWith('tec'));  // true
console.log('Irontec'.endsWith('Iron', 3)); // true
```

## includes(str, starts = 0)
```
console.log('Irontec'.includes('on'));      // true
console.log('Irontec'.includes('on', 4)); // false
```