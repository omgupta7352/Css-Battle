# Battle #25 - Flex

## #152 - Rook

[Link to the problem](https://cssbattle.dev/play/152)

![target](https://cssbattle.dev/targets/152.png)

```html
<div id="a">
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>
<div id="e"></div>
<p></p>
<style>
  body {
    background: #62306D;
    display: grid;
    place-content: center;
    place-items: center;
    gap: 5px;
  }
  div {
    background: #F7EC7D;
  }
  p {
    position: absolute;
    width: 120px;
    height: 136px;
    background: #62306D;
    border-radius: 50%;
    translate: -80px -5px;
    z-index: -1;
    box-shadow: 160px 0px #62306D;
  }
  #a {
    width: 90px;
    height: 60px;
    border-radius: 10px;
    display: flex;
    background: linear-gradient(transparent 50%, #F7EC7D 50%);
  }
  #b {
    height: 10px;
    width: 60px;
    border-radius: 5px;
  }
  #c {
    width: 90px;
    height: 65px;
    z-index: -2;
  }
  #d {
    height: 10px;
    width: 110px;
    border-radius: 5px;
  }
  #e {
    height: 25px;
    width: 140px;
    border-radius: 20px 20px 10px 10px;
  }
  #a > div:nth-of-type(odd) {
    width: 10px;
    height: 50px;
    border-radius: 5px 5px 0px 0px;
  }
  #a > div:nth-of-type(even) {
    background: #62306D;
    width: 30px;
    height: 45px;
    border-radius: 5px;
  }
</style>
```


