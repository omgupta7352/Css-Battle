# Battle #8 - Transition

## #44 - Stripes

[Link to the problem](https://cssbattle.dev/play/44)

![target](https://cssbattle.dev/targets/44.png)


```html
<div></div>
<style>
  body {
    background: #1A4341;
    display: grid;
    place-items: center;
  }
  div {
    width: 160px;
    height: 180px;
    background: repeating-linear-gradient(#F3AC3C 0px 20px, #1A4341 20px 40px);
  }
  div:before, div:after {
    content: "";
    display: block;
    width: 250px;
    height: 280px;
    border-radius: 50%;
    background: #1A4341;
  }
  div:before {
    translate: -220.5px -50px;
  }
  div:after {
    translate: 130.5px -330px;
  }
</style>

```
