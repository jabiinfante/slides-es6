# catch II

'catch' también capturará un error emitido desde una promesa resuelta:

<code><pre>
let promise = new Promise((resolve, reject) => {
  resolve('success');
});
promise.then(response => {
  throw new Error('nunca jamás!')
}).catch(error => {
  console.log("Promesa rechazada 😢 ", error); // nunca jamás!
});
</pre></code>
