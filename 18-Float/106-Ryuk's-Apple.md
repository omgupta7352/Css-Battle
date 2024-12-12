# Battle #18 - Float

## #106 - Ryuk's Apple

[Link to the problem](https://cssbattle.dev/play/106)

![target](https://cssbattle.dev/targets/106.png)

```html
<div id="left"></div>
<div id="right"></div>
<div id="stem"></div>
<div id="bite"></div>
<style>
  body {
    background: #000000;
    display: grid;
    place-content: center;
    grid-template-columns: 60px 60px;
    place-items: center;
  }
  #left, #right {
    width: 100px;
    height: 120px;
    background: #D4392D;
    border-radius: 50%;
    rotate: -30deg;
  }
  #right {
    rotate: 30deg;
  }
  #stem, #bite {
    position: absolute;
  }
  #stem {
    width: 10px;
    height: 40px;
    background: #D4392D;
    translate: 0px -60px;
  }
  #bite {
    width: 110px;
    height: 70px;
    background: #000000;
    border-radius: 50%;
    translate: -100px -11px;
    rotate: -27deg;
    box-shadow: -18px 35px;
  }
</style>
```
