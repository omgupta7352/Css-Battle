# Battle #17 - Chrismas

## #99 - Gift Box

[Link to the problem](https://cssbattle.dev/play/99)

![target](https://cssbattle.dev/targets/99.png)


```html
<div id="leftKnot"></div>
<div id="rightKnot"></div>
<div id="square">
  <div></div>
  <div id="vertical"></div>
</div>
<style>
  body {
    background: #AC474B;
    place-content: center;
    grid-template-columns: 30px 30px;
  }
  body, #square {
    display: grid;
    place-items: center;
  }
  #leftKnot, #rightKnot {
    width: 20px;
    height: 20px;
    border: 10px solid #FFFFFF;
    border-radius: 20px 20px 0px 20px;
  }
  #rightKnot {
    border-radius: 20px 20px 20px 0px;
  }
  #square {
    width: 140px;
    height: 140px;
    background: #FFFFFF;
    margin-top: 20px;
    grid-column: span 2;
  }
  div > div {
    background: #AC474B;
    height: 20px;
    width: 140px;
  }
  #vertical {
    position: absolute;
    rotate: 90deg;
  }
</style>
```
