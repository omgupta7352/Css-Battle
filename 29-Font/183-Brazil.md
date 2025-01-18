# Battle #29 - Font

## #183 - Brazil

[Link to the problem](https://cssbattle.dev/play/183)

![target](https://cssbattle.dev/targets/183.png)

```html
<div id="yellow"></div>
<div id="earth">
  <div id="white"></div>
</div>
<style>
  body {
    background: #009B3A;
    display: grid;
    place-items: center;
  }
  #yellow {
    width: 300px;
    height: 200px;
    background: #FEDF00;
    clip-path: polygon(50% 0, 100% 50%, 50% 100%, 0 50%);
  }
  div {
    position: absolute;
  }
  #earth {
    width: 120px;
    height: 120px;
    background: #002776;
    border-radius: 50%;
    overflow: hidden;
  }
  #white {
    border: 10px solid #FFFFFF;
    width: 190px;
    height: 190px;
    border-radius: 50%;
    translate: -73px 30px;
  }
</style>

```

