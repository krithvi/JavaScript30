# CSS Variables with JS

Start with:
```
:root {
    --spacing: 10px;
}
```
to declare the variables.   

Use it in values of attributes:
```
img {
    padding: var(--spacing);
}
```

With JavaScript, we can update the values of the CSS Variables.

* Store `'.controls input'` in const `inputs`
* Run `inputs.forEach` with `=>` to detect `change` and `mousemove`
To add suffix "px" to values of `spacing` and `blur` attributes, use `data-*` to store px under a dataset class.