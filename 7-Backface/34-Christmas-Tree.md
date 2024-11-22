# Battle #7 - Backface

## #34 - Christmas Tree

[Link to the problem](https://cssbattle.dev/play/34)

![target](https://cssbattle.dev/targets/34.png)

```html
<div id="top"></div>
<div id="middle"></div>
<div id="bottom"></div>
<style>
  body {
    background: #007065;
    display: grid;
    place-content: center;
  }
  div {
    border-left: 125px solid transparent;
    border-right: 125px solid transparent;
  }
  #top {
    border-bottom: 100px solid #FFEECF;
    translate: 0px 50px;
  }
  #middle {
    border-bottom: 100px solid #F5C181;
  }
  #bottom {
    border-bottom: 100px solid #00A79D;
    translate: 0px -50px;
    z-index: -1;
  }
</style>

```
