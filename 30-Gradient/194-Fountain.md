# Battle #30 - Gradient

## #194 - Fountain

[Link to the problem](https://cssbattle.dev/play/194)

![target](https://cssbattle.dev/targets/194.png)

```html
<div class="outer">
  <div></div>
</div>
<div class="outer" id="bottomLeft">
  <div></div>
</div>
<div class="outer" id="bottomRight">
  <div></div>
</div>
<style>
  body {
    background: #4FA07B;
    display: grid;
    place-items: center;
  }
  div {
    background: #4FA07B;
    border-radius: 70px 70px 0px 0px;
    border: 20px solid #0D1335;
    border-bottom: none;
  }
  .outer {
    position: absolute;
    width: 100px;
    height: 100px;
    display: grid;
    justify-content: center;
    align-content: end;
    translate: 0px -70px;
  }
  div > div {
    width: 20px;
    height: 60px;
  }
  #bottomLeft {
    translate: -60px 30px;
  }
  #bottomRight {
    translate: 60px 30px;
  }
  #bottomLeft:before, #bottomRight:before {
    content: "";
    display: block;
    background: #4FA07B;
    width: 20px;
    height: 60px;
  }
  #bottomLeft:before {
    translate: -40px 137px;
    box-shadow: 40px -37px #0D1335, 80px -17px #0D1335, 120px 3px #0D1335, 160px -17px #0D1335, 200px -37px #0D1335;
  }
  #bottomRight:before {
    translate: 80px 137px;
  }
</style>
```
