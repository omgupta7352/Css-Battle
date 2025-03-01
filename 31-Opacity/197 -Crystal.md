# Battle #31 - Opacity

## #197 - Crystal

[Link to the problem](https://cssbattle.dev/play/197)

![target](https://cssbattle.dev/targets/197.png)

```html
<p>
<p a>
<p b>
<p c></p>
<style>
  * {
    background: #5F133F;
  }

  p {
    position: fixed;
    width: 50;
    height: 220;
    background: linear-gradient(#F7BED9 32q, #F075B0 0 201q, #F7BED9 0);
    clip-path: polygon(50%0, 100%13.6%, 100%86.3%, 50%100%, 0%86.3%, 0%13.6%);
    margin: 32 167;
  }

  [a] {
    rotate: 60deg;
  }

  [b] {
    rotate: -60deg;
  }

  [c] {
    height: 50;
    width: 50;
    border-radius: 50%;
    background: #F7BED9;
    margin: 117 167;
  }
</style>
```
