## Лямбда-исчисление
1930 · Алонзо Чёрч 

---

### $\lambda x.x$

```js
const id = (x) => x;
```
<!-- .element: class="fragment inline-code" -->

---

### Термы

1. $x,y\ldots$ – переменные  <!-- .element: class="fragment" -->
1. $\lambda x.u$ – функции <!-- .element: class="fragment" -->
1. $(uv)$ – применение <!-- .element: class="fragment" -->

### Правила <!-- .element: class="fragment" -->

1. $\lambda x.x \to_\alpha \lambda y.y$ – конверсия <!-- .element: class="fragment" -->
1. $(\lambda x.x)(u) \to_\beta u$ – редукция<!-- .element: class="fragment" -->

---


### Есть $x \sin$ и $\sin x$ термы 😧

```js
const x = 3.14;
const sin = () => {/* ... */}

const main = () => x(sin)
```
<!-- .element: class="fragment" -->

```js
main() // => TypeError x is not a function
```
<!-- .element: class="fragment" -->

---

![slides/img/undefined_is_not_a_function.jpg](slides/img/undefined_is_not_a_function.jpg) <!-- .element: class="stretch" -->
