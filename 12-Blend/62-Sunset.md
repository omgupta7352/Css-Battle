# Battle #12 - Blend

## #62 - Sunset

[Link to the problem](https://cssbattle.dev/play/62)

![target](https://cssbattle.dev/targets/62.png)

```html
<div id="outer">
  <div id="sun"></div>
  <div id="leftHill"></div>
  <div id="rightHill"></div>
</div>
<style>
  body {
    background: #191919;
  }
  body, #outer {
    display: grid;
    place-items: center;
  }
  #outer {
    width: 150px;
    height: 200px;
    background: #F2AD43;
    border-radius: 75px 75px 20px 20px;
    position: relative;
    overflow: hidden;
  }
  div > div {
    position: absolute;
    width: 200px;
    height: 200px;
    border-radius: 50%;
  }
  #sun {
    width: 60px;
    height: 60px;
    background: #FFF58F;
    translate: 0px 20px;
  }
  #leftHill {
    background: #E08027;
    translate: -75px 50%;
  }
  #rightHill {
    background: #824B20;
    translate: 75px 50%;
  }
</style>
```
