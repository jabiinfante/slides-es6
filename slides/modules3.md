# import

La importación se hace haciendo referencia al fichero (sin extensión):
<pre><code>
import {nombre,sum} from 'module1';
console.log(nombre); // mi modulo
console.log(sum(2,2)); // 4
</code></pre>

Se pueden utilizar alias:

<pre><code>
import {nombre as name,sum} from 'module1';
console.log(name); // mi modulo
</code></pre>
