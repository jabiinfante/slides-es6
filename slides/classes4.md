# Clases IV (static)

<pre><code>
class Perro extends Animal {
  constructor(name) {
    super(name);
    this.type = 'dog';
    console.log(`Animal de tipo perro creado`);
  }
  static create(name) {
    return new Perro(name);
  }
}

var a1 = Perro.create('Pintxo');
</code></pre>
