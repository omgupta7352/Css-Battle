# Battle #17 - Chrismas

## #98 - Candle

[Link to the problem](https://cssbattle.dev/play/98)

![target](https://cssbattle.dev/targets/98.png)

```html
<div id="fire"></div>
<div id="dark"></div>
<div id="candle">
  <div id="top"></div>
</div>
<style>
  body {
    background: #14313E;
    display: grid;
    place-content: center;
    place-items: center;
  }
  #candle {
    width: 80px;
    height: 130px;
    background: #BA3E46;
    border-radius: 80px / 31px;
  }
  #top {
    background: #F3695A;
    height: 30px;
    border-radius: 50%;
  }
  #dark {
    width: 60px;
    height: 60px;
    background: #14313E;
    border-radius: 50px / 25px;
    position: absolute;
    translate: 0px -50px;
  }
  #fire {
    width: 30px;
    height: 50px;
    background: #F3AC3C;
    border-radius: 30px 0px;
    translate: 15px;
    z-index: 1;
  }
</style>
```
