# Battle #30 - Gradient

## #188 - Icecream Sticks

[Link to the problem](https://cssbattle.dev/play/188)

![target](https://cssbattle.dev/targets/188.png)


```html
<div class="v" id="lv"></div>
<div class="v dark"></div>
<div class="v" id="rv"></div>
<div id="top"></div>
<div class="dark"></div>
<div id="bottom"></div>
<style>
  body {
    display: grid;
    place-items: center;
    background: #FFFD9B;
  }
  div {
    position: absolute;
    width: 340px;
    height: 20px;
    background: #969610;
    border-radius: 10px;
  }
  .v {
    width: 20px;
    height: 240px;
  }
  #lv {
    translate: -80px;
  }
  #rv {
    translate: 80px;
  }
  #top {
    translate: 0px -80px;
  }
  #bottom {
    translate: 0px 80px;
  }
  .dark {
    background: #646521;
    z-index: 1;
  }
</style>
```
