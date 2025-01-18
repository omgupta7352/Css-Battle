# Battle #17 - Chrismas

## #100 - CSSBattle

[Link to the problem](https://cssbattle.dev/play/100)

![target](https://cssbattle.dev/targets/100.png)

```html
<div id="left"></div>
<div id="sword"></div>
<div id="bladeTop"></div>
<div id="sword2"></div>
<div id="bladeTop2"></div>
<div id="right"></div>
<style>
  body {
    background: #14313E;
    display: grid;
    place-items: center;
  }
  div {
    width: 20px;
    height: 150px;
    background: #FFDF00;
    position: absolute;
  }
  #left, #right {
    width: 40px;
    border-radius: 20px 0px 0px 20px;
  }
  :before, :after {
    display: block;
    content: "";
  }
  #left {
    translate: -117px;
  }
  #right {
    transform: rotate(180deg) translate(-117px);
  }
  #left:before, #right:before {
    background: #FFDF00;
    width: 10.5px;
    height: 40px;
    border-radius: 5px 0px 0px 5px;
    translate: -10px 55px;
  }
  #left:after, #right:after {
    background: #14313E;
    width: 16px;
    height: 100px;
    border-radius: 10px 0px 0px 10px;
    translate: 25px -15px;
  }
  #sword, #sword2 {
    height: 200px;
    transform: rotate(45deg) translate(-4px, 3px);
    border-radius: 25px;
  }
  #sword:before, #sword2:before {
    width: 30px;
    height: 140px;
    background: #FFDF00;
    translate: -5px 5px;
  }
  #sword:after, #sword2:after {
    width: 80px;
    height: 20px;
    background: #FFDF00;
    translate: -30px 0px;
  }
  #bladeTop, #bladeTop2 {
    background: #FFDF00;
    width: 22px;
    height: 22px;
    z-index: 1;
    translate: -62.5px -68px;
  }
  #bladeTop2 {
    translate: 62.5px -68px;
  }
  #sword2 {
    transform: rotate(-45deg) translate(4px, 3px);
  }
  #sword2:before {
    outline: 10px #14313E solid;
  }
</style>
```
