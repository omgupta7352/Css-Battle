# Battle #18 - Float

## #102 - One Piece

[Link to the problem](https://cssbattle.dev/play/102)

![target](https://cssbattle.dev/targets/102.png)


```html
<div id="skull">
  <div id="leftEye"></div>
  <div id="rightEye"></div>
</div>
<div class="bone" id="bone1"></div>
<div class="bone" id="bone2"></div>
<div class="bone" id="bone3"></div>
<div class="bone" id="bone4"></div>
<div id="teeth"></div>
<style>
  body {
    background: #000000;
    display: grid;
    place-items: center;
  }
  div {
    background: #FFFFFF;
  }
  #skull {
    width: 150px;
    height: 100px;
    border-radius: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    margin-top: 20px;
  }
  #leftEye, #rightEye {
    height: 50px;
    width: 40px;
    background: #000000;
    border-radius: 20px / 25px;
    rotate: 65deg;
  }
  #rightEye {
    rotate: -65deg;
  }
  .bone {
    position: absolute;
    width: 20px;
    height: 20px;
  }
  .bone:before {
    content: "";
    display: block;
    width: 25px;
    height: 25px;
    background: #FFFFFF;
    border-radius: 50%;
    translate: -18px 5px;
    box-shadow: 0px -15px #FFFFFF;
  }
  #teeth {
    position: absolute;
    width: 15px;
    height: 20px;
    translate: -20px 80px;
    color: #FFFFFF;
    box-shadow: 20px 0px, 40px 0px;
  }
  #bone1 {
    translate: -76.5px -37px;
    rotate: 45deg;
  }
  #bone2 {
    translate: 76.5px -37px;
    rotate: 135deg;
  }
  #bone3 {
    translate: -76.5px 57px;
    rotate: -45deg;
  }
  #bone4 {
    translate: 76.5px 57px;
    rotate: -135deg;
  }
</style>
```
