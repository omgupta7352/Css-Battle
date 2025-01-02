# Battle #26 - Initial

## #159 - Portal

[Link to the problem](https://cssbattle.dev/play/159)

![target](https://cssbattle.dev/targets/159.png)

```html
<div></div>
<div id="vertical"></div>
<div id="horizontal"></div>
<style>
  body {
    background: #F5D6B4;
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
    width: 150px;
    height: 150px;
    background: #D86F45;
  }
  #vertical, #horizontal {
    height: 250px;
    width: 50px;
  }
  #horizontal {
    rotate: 90deg;
  }
</style>
```
