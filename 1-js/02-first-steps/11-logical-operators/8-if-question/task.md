importance: 5

---

# A question about "if"

¿Cuál de estos `alert` se va a ejecutar?

¿Cuáles serán los resultados de las expresiones dentro de `if(...)`?

```js
if (-1 || 0) alert("first");
if (-1 && 0) alert("second");
if (null || (-1 && 1)) alert("third");
```