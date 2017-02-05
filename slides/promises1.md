# new Promise

Una promesa es un objeto que podrá ser devuelto por una función, o ser pasada como argumento.

Tienen una única responsabilidad; representan un evento que podrá ser manejado ninguna o multiples veces.

<code><pre>
let promise = new Promise((resolve, reject) => {
  // ...
  // Cuando cumplimos la promesa invocamos 'resolve'
  resolve('success');
  // ...
  // Si vamos a rechazar, invocamos 'reject'
  reject({error:true, erroDesc: 'error'});
});
</pre></code>
