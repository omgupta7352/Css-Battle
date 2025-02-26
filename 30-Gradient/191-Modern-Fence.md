# Battle #30 - Gradient

## #191 - Modern Fence

[Link to the problem](https://cssbattle.dev/play/191)

![target](https://cssbattle.dev/targets/191.png)


```html
<div id="top"></div>
<div id="center"></div>
<div id="bottom"></div>
<div id="left"></div>
<div id="right"></div>
<style>body{background:#2F2E59;display:grid;place-content:center;place-items:center;gap:46px}div{
    width: 240px;
    height: 20px;
    background: #EEECF6;
    border-radius: 10px;
    rotate: 30deg;
  }
  #left, #right {
    position: absolute;
    rotate: 90deg;
    width: 150px;
  }
  #right {
    right: 12px;
  }
  #center {
    width: 280px;
  }
  #left {
    left: 12px;
  }
  #top {
    translate: 11px 6.5px;
  }
  #bottom {
    translate: -11px -6.5px;
  }
</style>
```


