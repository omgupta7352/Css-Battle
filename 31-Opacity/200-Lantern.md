# Battle #31 - Opacity

## #200 - Lantern

[Link to the problem](https://cssbattle.dev/play/200)

![target](https://cssbattle.dev/targets/200.png)

```html
<div></div>
<div a></div>
<style>
  body {
    background: linear-gradient(to left,#fad3e5 175px, #8b0051 175px,#8b0051 225px,#fad3e5 225px);
  }
  div {
    width: 250px;
    height: 125px;
    background: #8b0051;
    margin: 27.5 auto;
    clip-path: polygon(50% 0, 100% 50%, 50% 100%, 0 50%);
  }
  [a] {
    margin: -32.5 auto;
  }
</style>
```
