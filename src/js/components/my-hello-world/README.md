# &lt;my-hello-world&gt;

A web component that contains some text.

## Styling with CSS

The background (div) is styleable using the part `back`.

## Example

```html
<my-hello-world></my-hello-world>

<my-hello-world class="background-pink"></my-hello-world>
```

```css
my-hello-world.background-pink::part(back) {
  background: #FFC0CB;
}
```
