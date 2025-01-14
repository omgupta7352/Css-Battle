 

# Battle #30 - Gradient

## #189 - Triangle Hook

[Link to the problem](https://cssbattle.dev/play/189)

![target](https://cssbattle.dev/targets/189.png)

```html
<div l></div><div m></div><div r><style>
  body {
    background: #D669EC;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    background: #FDFBF8;
  }
  [l]{
    border-top: 40px solid #D669EC;
    border-bottom: 40px solid #D669EC; 
    border-right:80px solid #FDFBF8;
    clip-path: polygon(0 0, 100% 0, 100% 18%, 40% 50%, 100% 82%, 100% 100%, 0 100%);
    margin-right: 30px;

  }
  [m]{
    width: 230px;
    height: 20px;
    position: absolute;
  }
  [r]{width:180;
    height: 180px;
    background: linear-gradient(to right, #FDFBF8 110px, #D669EC 110px 130px, #FDFBF8 0);clip-path:polygon(0 0,100% 50%,0 100%)
```


# Battle #30 - Gradient

## #190 - Power Chip

[Link to the problem](https://cssbattle.dev/play/190)

![target](https://cssbattle.dev/targets/190.png)

```html
<div></div>
<div id="right"><style>
  body {
    background: #E3516E;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
  }
  div {
    width: 130px;
    height: 150px;
    background: #FADE8B;
    display: grid;
    justify-items: center;
    align-content: end;
    clip-path: polygon(0 0, 67% 0, 100% 46%, 100% 100%, 0 100%);
  }
  #right {
    clip-path: polygon(0 46%, 33% 0, 100% 0, 100% 100%, 0 100%);
  }div:before,div:after {content:"";display:block}
  div:before{
    border-left: 25px solid #FADE8B;
    border-right: 25px solid #FADE8B;
    border-bottom: 40px solid #E3516E}
  div:after{background:#E3516E;width:20;height:50
```


# Battle #30 - Gradient

## #191 - Modern Fence

[Link to the problem](https://cssbattle.dev/play/191)

![target](https://cssbattle.dev/targets/191.png)

```html
<div id="top"></div>
<div id="center"></div>
<div id="bottom"></div>
<div id="left"></div>
<div id="right"></div>
<style>body{background:#2F2E59;display:grid;place-content:center;place-items:center;gap:46px}div{
    width: 240px;
    height: 20px;
    background: #EEECF6;
    border-radius: 10px;
    rotate: 30deg;
  }
  #left, #right {
    position: absolute;
    rotate: 90deg;
    width: 150px;
  }
  #right {
    right: 12px;
  }
  #center {
    width: 280px;
  }
  #left {
    left: 12px;
  }
  #top {
    translate: 11px 6.5px;
  }
  #bottom {
    translate: -11px -6.5px;
  }
</style>
```


# Battle #30 - Gradient

## #192 - Abstract Firefly

[Link to the problem](https://cssbattle.dev/play/192)

![target](https://cssbattle.dev/targets/192.png)

```html
<div></div>
<style>
  body {
    background: #1D471D;
    display: grid;
    place-content: center;
  }
  div {
    width: 280px;
    height: 150px;
    background: #CCE58E;
    clip-path: polygon(33% 38%, 21% 42%, 0 0, 41.5% 11%, 50% 33%, 58.5% 11%, 100% 0, 79% 42%, 67% 38%, 69% 61%, 50% 100%, 31% 62%);
  }
</style>
```


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
