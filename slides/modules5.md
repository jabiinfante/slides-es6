# import (default)

La importación de un módulo con valor default, es sencilla:
<pre><code>
import doubler from 'module2';
console.log(doubler(2,3)); // [4,6]
</code></pre>

Se pueden importar también los exportados con nombre:
<pre><code>
import doubler,{PI} from 'module2';
console.log(doubler(2,3)); // [4,6]
console.log(PI); // 3.14159
</code></pre>
