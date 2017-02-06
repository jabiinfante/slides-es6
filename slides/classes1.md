# Clases I (constructor)

<pre><code>
class Animal {

  constructor(name) {
    this.name = name
    console.log(`Animal de nombre ${this.name} creado`);
  }
  talk() {
    console.log('Soy un animal, no se hablar.');
  }
}

var a1 = new Animal('Pintxo');
a1.talk();
</code></pre>
