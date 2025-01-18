# Battle #24 - Offset

## #144 - Long Heart

[Link to the problem](https://cssbattle.dev/play/144)

![target](https://cssbattle.dev/targets/144.png)

```html
<div id="topLeft"></div>
<div id="topRight"></div>
<div id="bottomLeft"></div>
<div id="bottomRight"></div>
<style>
  body {
    background: #62306D;
    display: grid;
    margin: 0px;
    grid-template-columns: 75px auto;
    align-content: end;
  }
  div {
    height: 125px;
    background: #F7EC7D;
  }
  #topLeft {
    border-radius: 40px 40px 0px 0px;
  }
  #bottomLeft {
    width: 125px;
    position: absolute;
    align-self: end;
  }
  #bottomRight {
    height: 75px;
    width: 200px;
    border-radius: 0px 40px 40px;
  }
  #topRight {
    background: #62306D;
    z-index: 1;
    border-radius: 25px;
  }
</style>

```
