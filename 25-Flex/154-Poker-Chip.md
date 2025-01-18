# Battle #25 - Flex

## #154 - Poker Chip

[Link to the problem](https://cssbattle.dev/play/154)

![target](https://cssbattle.dev/targets/154.png)

```html
<div></div>
<div id="oblique1"></div>
<div id="oblique2"></div>
<div id="horizontal"></div>
<div id="innerCircle"></div>
<style>
  body {
    background: radial-gradient(circle, #0B2429 80px, #FCBE5C 80px 95px, #0B2429 95px 105px, #998235 100px);
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
    width: 30px;
    height: 200px;
    background: #0B2429;
  }
  #innerCircle {
    width: 120px;
    height: 120px;
    border: 10px solid #FCBE5C;
    border-radius: 50%;
  }
  #oblique1 {
    rotate: 45deg;
  }
  #oblique2 {
    rotate: -45deg;
  }
  #horizontal {
    rotate: 90deg;
  }
</style>
```


