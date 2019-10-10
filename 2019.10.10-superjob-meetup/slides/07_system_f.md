# system F

1972 – 1974 

---

## $\Lambda \alpha .\lambda x.x : \forall\alpha.\alpha \to \alpha$

---

```ts
function id<T>(x: T): T { return x }
```

```ts
const foo: string = id('a'); // OK 
const bar: number = id(3); // OK 
```
<!-- .element: class="fragment" -->

```ts
const baz: string = id(42); // Error 

function func<T>(x: T): T {
  return "foo"; // Error
}
```
<!-- .element: class="fragment" -->

---

```ts
const stringIdentity = (value: string): string => value;

const booleanIdentity = (value: boolean): boolean => value;

const numberIdentity = (value: number): number => value;

// ...
```
