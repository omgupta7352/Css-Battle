# Battle #18 - Float

## #107 - Sealing Wand

[Link to the problem](https://cssbattle.dev/play/107)

![target](https://cssbattle.dev/targets/107.png)

```html
<div id="beak"></div>
<div id="head"></div>
<div id="red"></div>
<div id="neck"></div>
<style>
  body {
    background: #161616;
    display: grid;
    justify-items: center;
    align-content: end;
    margin: 0px;
  }
  #neck {
    width: 20px;
    height: 98px;
    background: #E96A23;
  }
  #red {
    width: 30px;
    height: 27px;
    background: #A22015;
    translate: 0px 1px;
    border-radius: 0px 0px 10px 10px;
  }
  #head {
    width: 60px;
    height: 60px;
    background: radial-gradient(#161616 10px, #A22015 10px 15px, #FFFFFF 15px 25px, #A22015 25px);
    border-radius: 50%;
    translate: 0px 5px;
  }
  #beak {
    position: absolute;
    width: 80px;
    height: 40px;
    background: #E96A23;
    align-self: center;
    translate: 40px -1px;
    border-radius: 0px 40px 5px 0px;
  }
  .feathers {
    position: absolute;
    width: 55px;
    height: 12px;
    background: #FFFFFF;
    align-self: center;
    translate: -43px -12px;
    border-radius: 0px 0px 0px 12px;
    z-index: 1;
  }
  #middle {
    width: 40px;
    translate: -35px;
  }
  #bottom {
    width: 25px;
    translate: -28px 12px;
  }
</style>
```
