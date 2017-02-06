# Clases III (set/get)

<pre><code>
class Perro extends Animal {
  constructor(name) {
    super(name);
    this.type = 'dog';
    this._breed = '';
    console.log(`Animal de tipo perro creado`);
  }
  set breed(breed) {
    // comprobar raza valida??
    this._breed = breed;
  }

  get breed() {
    return this._breed;
  }
}

var a1 = new Perro('Pintxo');
a1.breed = 'Pastor Alemán';
console.log(a1.breed);
</code></pre>
