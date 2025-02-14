# Battle #25 - Flex

## #151 - Pawn

[Link to the problem](https://cssbattle.dev/play/151)

![target](https://cssbattle.dev/targets/151.png)


```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>
<p></p>
<style>
  body {
    background: #F5D6B4;
    display: grid;
    place-content: center;
    place-items: center;
    gap: 5px;
  }
  div {
    background: #D86F45;
  }
  p {
    position: absolute;
    width: 120px;
    height: 136px;
    background: #F5D6B4;
    border-radius: 50%;
    translate: -80px -5px;
    z-index: -1;
    box-shadow: 160px 0px #F5D6B4;
  }
  #a {
    width: 50px;
    height: 50px;
    border-radius: 50%;
  }
  #b {
    height: 20px;
    width: 80px;
    border-radius: 5px 5px 15px 15px;
  }
  #c {
    width: 90px;
    height: 65px;
    z-index: -2;
  }
  #d {
    height: 40px;
    width: 140px;
    border-radius: 20px 20px 10px 10px;
  }
</style>
```
