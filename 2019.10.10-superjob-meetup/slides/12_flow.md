# Flow 

2014 · facebook 

---

- Суперсет Javascript
- Статическая проверка типов

---

#### Номинальная типизация для классов

```
class Foo { method(input: string) { } }
class Bar { method(input: string) { } }

const foo: Foo = new Bar(); // Error!
```

---

#### Структурная типизация для объектов и функци

```ts
type F = (input: string) => void;
function f(input: string) { }
const f2: F = f; //  OK

type O = { key: string };
const foo = { key: "value" };
const bar: O = foo; //  OK
```
