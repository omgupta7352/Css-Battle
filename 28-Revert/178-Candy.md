# Battle #28 - Revert

## #178 - Candy

[Link to the problem](https://cssbattle.dev/play/178)

![target](https://cssbattle.dev/targets/178.png)


```html
<div id="left"></div>
<div id="center">
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>
<div id="right"></div>
<style>
  body {
    background: #CBE8DD;
  }
  body, div {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px
  }
  #center {
    width: 180px;
    height: 100px;
    background: #007192;
    border-radius: 10px;
  }
  #center > div {
    width: 10px;
    height: 110px;
    background: #CBE8DD;
    rotate: 20deg;
  }
  #left, #right {
    width: 30px;
    height: 80px;
    background: #007192;
    clip-path: polygon(0 0, 100% 37.5%, 100% 62.5%, 0 100%);
  }
  #right {
    rotate: 180deg;
  }
</style>
```
