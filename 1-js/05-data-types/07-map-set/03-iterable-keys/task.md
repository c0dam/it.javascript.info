importance: 5

---

# Chiavi iterabili

<<<<<<< HEAD:1-js/05-data-types/07-map-set-weakmap-weakset/03-iterable-keys/task.md
Vogliamo avere un rray di `map.keys()` e poterci lavorare.

Ma c'è un problema:
=======
We'd like to get an array of `map.keys()` in a variable and then do apply array-specific methods to it, e.g. `.push`.

But that doesn't work:
>>>>>>> 9bfc8cfa9c055bdcbc8f40471fc52e011687a728:1-js/05-data-types/07-map-set/03-iterable-keys/task.md

```js run
let map = new Map();

map.set("name", "John");

let keys = map.keys();

*!*
// Error: keys.push is not a function
keys.push("more");
*/!*
```

Perchè? Come possiamo sistemare il codice per rendere `keys.push` funzionante?
