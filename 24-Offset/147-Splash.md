# Battle #24 - Offset

## #147 - Splash

[Link to the problem](https://cssbattle.dev/play/147)

![target](https://cssbattle.dev/targets/147.png)

```html
<div id="left"></div>
<div></div>
<div id="right"></div>
<style>
  body {
    background: #6592CF;
    display: grid;
    justify-items: end;
    align-items: end;
    margin: 0px;
  }
  div {
    width: 200px;
    height: 50px;
    background: #060F55;
    position: absolute;
    transform-origin: 87.5% center;
    rotate: 45deg;
    border-radius: 25px;
    translate: 7.5px 7.5px;
  }
  #left {
    height: 30px;
    translate: 18px 93px;
  }
  #right {
    height: 30px;
    translate: 103px 8px
  }
</style>
```

