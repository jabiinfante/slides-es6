# Funciones arrow

Las funciones arrow son una forma *corta* de funciones anónimas.

Siempre se ejecutan en el contexto de *this* sin necesidad de _bind_, _call_ o _apply_ (o _var self=this_).

<pre><code>
    () => { /* code */ }       // sin argumentos
     x => { /* code */ }       // 1 argumento
(x, y) => { /* code */ }       // n argumentos

    x => { return x * x } // bloque
    x => x * x            // una única expresión
</code></pre>