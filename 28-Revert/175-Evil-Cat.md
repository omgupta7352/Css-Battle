# Battle #28 - Revert

## #175 - Evil Cat

[Link to the problem](https://cssbattle.dev/play/175)

![target](https://cssbattle.dev/targets/175.png)

```html
<div id="ear1"></div>
<div id="ear2"></div>
<div id="head">
  <div></div>
  <div></div>
</div>
<div id="nose"></div>
<style>
  body {
    background: #ED6A9D;
  }
  body, div {
    display: grid;
    place-items: center;
    place-content: center;
  }
  #head {
    width: 180px;
    height: 150px;
    background: #050044;
    border-radius: 50%;
    margin-top: 30px;
    grid-auto-flow: column;
    gap: 30px;
  }
  #head > div {
    width: 40px;
    height: 40px;
    background: #FFC100;
    border-radius: 20px 0px;
    rotate: 45deg;
    margin-bottom: 30px;
  }
  #head > div:before {
    content: "";
    display: block;
    height: 30px;
    width: 10px;
    background: #050044;
    rotate: -45deg;
    border-radius: 50%;
  }
  #nose, #ear1, #ear2 {
    position: absolute;
  }
  #nose {
    border-left: 15px solid transparent;
    border-right: 15px solid transparent;
    border-top: 15px solid #ED6A9D;
    margin-top: 85px;
  }
  #ear1, #ear2 {
    height: 60px;
    width: 50px;
    background: linear-gradient(37deg, #050044 62%, #ED6A9D 0);
    z-index: -1;
  }
  #ear1 {
    translate: -53.5px -57px;
    rotate: -3.5deg;
  }
  #ear2 {
    translate: 53.5px -57px;
    rotate: 3.5deg;
    scale: -1 1;
  }
</style>
```
