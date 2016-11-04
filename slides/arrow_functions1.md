# Funciones arrow (II)

El contexto del bloque (o expresión) será siempre **this**.

Antes (ES5):
<pre><code>
    function Coche() {
        this.kmts = 0;
        var self = this;
        setInterval(function() {
            self.kmts++;
        },1000);
    }
</code></pre>

Ahoras (ES6):
<pre><code>
    function Coche() {
        this.kmts = 0;
        setInterval(() => {
            this.kmts++;
        },1000);
    }
</code></pre>