# const

_const_ define una constante en el ámbito del bloque en el que se declara

La variable contiene un valor inmutable.

<pre><code>
const PI = 3.14159

if (PI > 2) {
    const EULER = 0.57721
    
//    PI = 3.1416; //TypeError: Assignment to constant variable
    
    console.log(PI); // 3.14159:wq

    console.log(EULER); // 0.57721
}

console.log(PI); // 3.14159
console.log(EULER); // undefined

</code></pre>
