# Battle #28 - Revert

## #176 - Castlevania

[Link to the problem](https://cssbattle.dev/play/176)

![target](https://cssbattle.dev/targets/176.png)

```html
<div class="towerRoof"></div>
<div id="roofCenter"></div>
<div class="towerRoof"></div>
<div>
  <div></div>
</div>
<div id="center">
  <div id="door"></div>
</div>
<div>
  <div></div>
</div>
<style>
  body, div {
    display: grid;
  }
  body {
    background: #A6D6AE;
    place-content: center;
    grid-template: 80px 100px / 50px 100px 50px;
  }
  div {
    width: 50px;
    height: 120px;
    background: #3A0F09;
    justify-self: center;
    align-self: end;
  }
  #center {
    width: 100px;
    height: 85px;
  }
  #roofCenter, .towerRoof {
    height: 0px;
    width: 0px;
  }
  #roofCenter {
    border-left: 50px solid #A6D6AE;
    border-right: 50px solid #A6D6AE;
    border-bottom: 35px solid #3A0F09;
    translate: 0px 15px;
  }
  .towerRoof {
    border-left: 40px solid #A6D6AE;
    border-right: 40px solid #A6D6AE;
    border-bottom: 60px solid #3A0F09;
    align-self: start;
  }
  div > div {
    width: 20px;
    height: 25px;
    background: #BB9213;
    border-radius: 30px 30px 0px 0px;
    align-self: start;
    margin-top: 10px;
  }
  #door {
    align-self: end;
    width: 60px;
    height: 50px;
  }
</style>
```
