## Простое типизированое лямбда-исчисление

1940 · Алонзо Чёрч 

---

## $\lambda x.x: A \to A$

```
const id: A => A = (x) => x
```
<!-- .element: class="fragment inline-code" -->

---

### Термы

1. $x: A, y:B\ldots$ – переменные <!-- .element: class="fragment" -->
1. $\lambda x.u: A \to B$ – функции <!-- .element: class="fragment" -->
1. $(uv), u: A \to B, v: A$ – применение  <!-- .element: class="fragment" -->

### Типы <!-- .element: class="fragment" -->

1. $A, B, ...$ – простые типы <!-- .element: class="fragment" -->
1. $A \to B$  – типы функций <!-- .element: class="fragment" -->

---

## Можно только $\sin x$ 😌

$\sin: \mathbb R \to \mathbb R$ and $x : \mathbb R$
