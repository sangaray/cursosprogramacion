# Complex Selectors and Relations

The combined or complex selectosrs are used to apply stiles bades in the specificrealtions of several elements.

**structure**

```css
selector1 selector2,
selector3 {
  property: value;
}
```

El problema principal se debe a la herencia de CSS:

- **Conflicto de estilos:** A direct rule always takes precedence over an inherited value, regardless of the file order.
