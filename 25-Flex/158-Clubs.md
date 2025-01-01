# Battle #25 - Flex

## #158 - Clubs

[Link to the problem](https://cssbattle.dev/play/158)

![target](https://cssbattle.dev/targets/158.png)

```html
<div id="top"></div>
<div id="left"></div>
<div id="right"></div>
<div id="bottom"></div>
<style>
  body {
    background: #4F77FF;
    display: grid;
    place-content: center;
    place-items: center;
    grid-template: 140px 0px / 90px 90px;
  }
  div {
    width: 100px;
    height: 100px;
    background: #1038BF;
    border-radius: 50%;
  }
  #top, #bottom {
    grid-column: span 2;
  }
  #bottom {
    border-radius: 0px;
    translate: 0px -20px;
    z-index: -1;
  }
  #left {
    box-shadow: -10px 40px #4F77FF;
  }
  #right {
    box-shadow: 10px 40px #4F77FF;
  }
</style>
```

