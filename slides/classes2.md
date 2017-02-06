# Clases II (extends/super)

<pre><code>
class Perro extends Animal {

  constructor(name) {
    super(name);
    this.type = 'dog';
    console.log(`Animal de tipo perro creado`);
  }
  talk() {
    console.log('GUAU!');
  }
}

var a1 = new Perro('Pintxo');
a1.talk();
</code></pre>
