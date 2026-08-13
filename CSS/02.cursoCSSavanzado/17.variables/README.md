# Variables o Custom Properties

It is a name given to a specific action. That helps to asign properties more easily. Its function is to avoid to repeat code throughout the document and when need to change the value of a property in the web page repeated in several places you dont have to change it in every one of that places, changing the variable changes the value in all the places.

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

## More About Custom Properties

[Como Usar Las Variables en CSS](https://www.youtube.com/watch?v=EsVvrcmOjQw)

**Ejemplo**

```css
:root {
  --color: #f3f3f3;
  --bg-color: #3f3f3f;
  --font-size: 1.5rem;
}

body {
  background-color: var(--bg-color);
  color: var(--color);
  font-size: var(--font-size);
}
```
