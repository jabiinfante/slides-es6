# Promise.all

Con esta funcionalidad, podemos agregar varias promesas como si se tratara de una única.



<code><pre>
let promise1 = new Promise((resolve, reject) => { resolve('promise1')});
let promise2 = new Promise((resolve, reject) => { resolve('promise2')});
Promise.all([promise1, promise2])
  .then(response => {
    // Destricturing ;)
    let [responsePromise1, responsePromise2] = response;
  });
</pre></code>

Si una de ellas es rechazada, la nueva promesa no será resuelta.
