# Iterator
El protocolo __Iterator__ especifica como se debe producir una secuencia estándar de valores.

Se considera un objeto __Iterator__ si implementa el método _next()_ que devuelve una estructura:
<code><pre>
 {
   done: (boolean),
   value
 }
 </pre></code>
