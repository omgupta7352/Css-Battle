# Battle #30 - Gradient

## #193 - Galver

[Link to the problem](https://cssbattle.dev/play/193)

![target](https://cssbattle.dev/targets/193.png)


```html
<div id="vertical"></div>
<div id="horizontal"></div>
<div id="pink"></div>
<style>
  body {
    background: radial-gradient(circle, #8B0051 50px, #FCDDEB 50px 65px, #8B0051 65px 80px, #FCDDEB 80px);
    display: grid;
    place-items: center;
  }
  #vertical, #horizontal {
    width: 30px;
    height: 230px;
    background: #8B0051;
    position: absolute;
    border-radius: 15px;
    clip-path: polygon(0 0, 100% 0, 100% 7%, 50% 50%, 100% 93%, 100% 100%, 0 100%, 0 93%, 50% 50%, 0 7%);
  }
  #horizontal {
    rotate: 90deg;
  }
  #pink {
    width: 70px;
    height: 70px;
    background: radial-gradient(circle, transparent 20px, #F180B6 20px);
    border-radius: 50%;
    z-index: 1;
  }
</style>
```
