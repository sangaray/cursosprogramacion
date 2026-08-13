# Variables

It is a name given to a specific action. That helps to asign properties more easily.

## Types of variables

- Global variables = they are variables that are used in all the document. Can acces different selectors

**Structure**

````css
:root {
  --color: black;
}

**Use** ```css div {
  color: var(--color) * *;
}
````

- Local variables = they are variables that are used in a specific element. Only can access one selector

**Structure**

```css
- .bock {
  color: #8cacea
  --color: black;
}
```

**Use**

```css
div {
  color: var(--color)
}
}
```
