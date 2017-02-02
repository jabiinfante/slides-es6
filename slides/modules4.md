# import (wildcard)

Se puede importar todo el módulo mediante un wildcard (*)

<pre><code>
import * from 'module1';
console.log(nombre); // mi modulo
console.log(sum(2,2)); // 4
</code></pre>

También se puede (**y debe**) combinar con un alias:
<pre><code>
import * as module1 from 'module1';
console.log(module1.name); // mi modulo
console.log(module1.sum(2,2)); // 3.14159
</code></pre>
