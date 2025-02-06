# Battle #18 - Float

## #105 - Ryuk

[Link to the problem](https://cssbattle.dev/play/105)

![target](https://cssbattle.dev/targets/105.png)


```html
<div id="top"></div>
<div id="left"></div>
<div id="leftInside"></div>
<div id="right"></div>
<div id="rightInside"></div>
<style>
  body {
    background: #BAC7CE;
    margin: 0px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 100px;
  }
  #top {
    position: absolute;
    width: 130px;
    height: 130px;
    background: #475862;
    align-self: start;
    rotate: 45deg;
    translate: 0px -65px;
  }
  #leftInside, #rightInside {
    position: absolute;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background: radial-gradient(#4E2B24 15px, #000000 15px 20px, #868A64 20px);
    box-shadow: inset 0px 15px #5A6042;
  }
  #leftInside {
    translate: -110px 40px;
  }
  #rightInside {
    translate: 110px 40px;
  }
  #left, #right {
    width: 120px;
    height: 120px;
    background: #000000;
    margin-top: 80px;
    border-radius: 0px 60px;
    rotate: -15deg;
  }
  #right {
    rotate: 105deg;
  }
</style>
```
