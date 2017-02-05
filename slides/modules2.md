# export (default)

Un módulo puede exportar un valor por defecto (__default__).

Útil en estos casos:
 - Contiene toda la funcionalidad del módulo.
 - Módulo con una única funcionalidad.

<pre><code>
#module2.js
export default function(...items) {
  return items.map(x=>x*2);
};

// El módulo puede seguir devolviendo valores nominativos
const PI=3.14159;
export {PI};

</code></pre>
