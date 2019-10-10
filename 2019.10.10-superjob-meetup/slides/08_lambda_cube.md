# Лямбда-куб

1991 

---

![slides/img/lambdaCube.png](slides/img/lambdaCube.png) <!-- .element: style="width: 70%" --> 

---

## Зависимые типы в `Idris`

```haskell
v: Vect 3 Integer
v = [1,2,3]

cons: a -> Vect n a -> Vect (n + 1) a
```

---

### Типовое лямбда исчисление

Основа для разработки новых систем типизации для языков програмирования

---

## Типы

- Безопасность <!-- .element: class="fragment" -->
- Семантика  <!-- .element: class="fragment" -->
- Абстракция <!-- .element: class="fragment" -->
