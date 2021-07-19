# CSS Inheritance

Selects the `<a>` immediately under the `<section>` element, but not the ones within the `<p>` element that is a grand-child.

![](https://raw.githubusercontent.com/hoc-demos/images/main/css-inheritance.png)
```css
body {
    background-color:red;
    color:white;
    text-transform: uppercase;
}

/* overrides inherited background-color */
h1 {
    background-color:purple;
}

/* overrides inherited background-color, text-transform */
p {
    background-color:orange;
    text-transform: none;
}

```
