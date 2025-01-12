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


# Battle #29 - Font

## #184 - India

[Link to the problem](https://cssbattle.dev/play/184)

![target](https://cssbattle.dev/targets/184.png)

```html
<div id="circle"></div>
<div></div>
<div id="a"></div>
<div id="b"></div>
<style>
  body {
    background: linear-gradient(#F19E4B 100px, #FFFFFF 100px 200px, #3F8627 0);
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
    width: 4px;
    height: 70px;
    background: #00007B;
  }
  #a {
    rotate: 60deg;
  }
  #b {
    rotate: 120deg;
  }
  #circle {
    width: 80px;
    height: 80px;
    background: radial-gradient(#00007B 10px, #FFFFFF 10px 30px, #00007B 0);
    border-radius: 50%;
  }
</style>
```


# Battle #29 - Font

## #185 - South Korea

[Link to the problem](https://cssbattle.dev/play/185)

![target](https://cssbattle.dev/targets/185.png)

```html
<p><a><a><a i><a a><a a><a a><p><a a><a><a i a><a><a a><a>
<style>
  html {
    background: radial-gradient(1q, #0000, 64q, #fff),
      radial-gradient(1q, #CD2E3A, 30px, #0000)-32q,
      radial-gradient(1q, #0047A0, 32q, #0000)32q,
      linear-gradient(#CD2E3A 50%, #0047A0 0);
  }
  p {
    rotate: 30deg;margin: 141 59
  }
  p+p {
    rotate: 150deg; margin: -159 59
  }
  a {
    padding: 21.5 5;
    background: #000;
    margin: 3;
  }
  [i] {
    margin-right: 173
  }
  [a] {
    background: linear-gradient(#000, 45%, #fff 0 55%, #000 0)
  }
</style>
```


# Battle #29 - Font

## #186 - Guernsey

[Link to the problem](https://cssbattle.dev/play/186)

![target](https://cssbattle.dev/targets/186.png)

```html
<div id="redVertical"></div>
<div id="redHorizontal"></div>
<div id="yellowVertical"></div>
<div id="yellowHorizontal"></div>
<style>
  body {
    display: grid;
    place-items: center;
    margin: 0px;
  }
  #redVertical, #redHorizontal {
    width: 80px;
    height: 400px;
    background: #E8112D;
  }
  div {
    position: absolute;
  }
  #yellowVertical, #yellowHorizontal {
    width: 20px;
    height: 230px;
    background: #F9DD16;
  }
  #yellowHorizontal, #redHorizontal {
    rotate: 90deg;
  }
  #yellowVertical:before, #yellowVertical:after, #yellowHorizontal:before, #yellowHorizontal:after {
    content: "";
    display: block;
    border-left: 20px solid transparent;
    border-right: 20px solid transparent;
    border-top: 30px solid #F9DD16;
    translate: -10px;
  }
  #yellowVertical:after, #yellowHorizontal:after {
    translate: -10px 170px;
    rotate: 180deg;
  }
</style>
```





# Battle #30 - Gradient

## #187 - Striped Triangle

[Link to the problem](https://cssbattle.dev/play/187)

![target](https://cssbattle.dev/targets/187.png)

```html
<div></div>
<style>
  body {
    background: #40234B;
    display: grid;
    place-items: center;
  }
  div {
    width: 230px;
    height: 200px;
    background: linear-gradient(120deg, #A94EA4 14.5px, #40234B 0 24.5px, #A94EA4 0 40.5px, #40234B 0 50.5px, #A94EA4 0 66.5px, #40234B 0 76.5px, #A94EA4 0 92.5px, #40234B 0 102.5px, #A94EA4 0 118.5px, #40234B 0 128.5px, #A94EA4 0 144.5px, #40234B 0 154.5px, #A94EA4 0 170.5px, #40234B 0 180.5px, #A94EA4 0 190px);
    clip-path: polygon(0 0, 100% 0, 50% 100%);
  }
</style>
```


# Battle #30 - Gradient

## #188 - Icecream Sticks

[Link to the problem](https://cssbattle.dev/play/188)

![target](https://cssbattle.dev/targets/188.png)

```html
<div class="v" id="lv"></div>
<div class="v dark"></div>
<div class="v" id="rv"></div>
<div id="top"></div>
<div class="dark"></div>
<div id="bottom"></div>
<style>
  body {
    display: grid;
    place-items: center;
    background: #FFFD9B;
  }
  div {
    position: absolute;
    width: 340px;
    height: 20px;
    background: #969610;
    border-radius: 10px;
  }
  .v {
    width: 20px;
    height: 240px;
  }
  #lv {
    translate: -80px;
  }
  #rv {
    translate: 80px;
  }
  #top {
    translate: 0px -80px;
  }
  #bottom {
    translate: 0px 80px;
  }
  .dark {
    background: #646521;
    z-index: 1;
  }
</style>
```


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
