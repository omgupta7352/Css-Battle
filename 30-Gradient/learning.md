# Battle #27 - Relative

## #167 - React India

[Link to the problem](https://cssbattle.dev/play/167)

![target](https://cssbattle.dev/targets/167.png)

```html
<div></div>
<div id="green"></div>
<div id="orange"></div>
<style>
  body {
    background: radial-gradient(circle, #73C6EA 20px, #0D1335 20px);
    display: grid;
    place-items: center;
  }
  div {
    width: 230px;
    height: 90px;
    border: 10px solid #FBFAE2;
    border-radius: 50%;
    position: absolute;
  }
  #green {
    rotate: -60deg;
    border-color: #4FA07B;
  }
  #orange {
    rotate: 60deg;
    border-color: #DC6638;
  }
</style>

```


# Battle #27 - Relative

## #168 - Carpet

[Link to the problem](https://cssbattle.dev/play/168)

![target](https://cssbattle.dev/targets/168.png)

```html
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body {
    background: #0D1335;
    margin: 0px;
    display: grid;
    grid-template: 280px / 330px 0px;
  }
  div {
    width: 70px;
    height: 20px;
    background: #DC6638;
    box-shadow: 0px 0px 0px 20px #0D1335, 0px 0px 0px 40px #DC6638, 0px 0px 0px 60px #0D1335, 0px 0px 0px 80px #DC6638, 0px 0px 0px 100px #0D1335, 0px 0px 0px 120px #DC6638;
  }
</style>
```


# Battle #27 - Relative

## #169 - Abstract Plate

[Link to the problem](https://cssbattle.dev/play/169)

![target](https://cssbattle.dev/targets/169.png)

```html
<p></p><p></p>
<style>
  * {
    background: radial-gradient(circle, #4FA07B 55px, 0, #0D1335 65px, 0, #4FA07B 85px, 0, #0D1335 95px, 0, #4FA07B 115px, 0, #0D1335 125px, 0, #4FA07B);
  }
  body {
    background: #FBFAE2;
    margin: 32px 45px;
    clip-path: polygon(0 0, 0 100%, 50% 59%, 100% 100%, 100% 0, 50% 41%);
  }
  p {
    position: fixed;
    inset: 0;
    clip-path: polygon(55px 34px, 55px 234px, 190px 150px, 166px 134px, 190px 118px);
  }
  p + p {
    scale: -1;
  }
</style>

```


# Battle #27 - Relative

## #170 - Party Hat

[Link to the problem](https://cssbattle.dev/play/170)

![target](https://cssbattle.dev/targets/170.png)

```html
<div></div>
<div id="orange"></div>
<div id="white"></div>
<style>
  body {
    background: #73C6EA;
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
    border-left: 125px solid transparent;
    border-right: 125px solid transparent;
    border-bottom: 180px solid #0D1335;
  }
  #orange {
    border-bottom: 140px solid #DC6638;
    margin-top: 40px;
  }
  #white {
    border-bottom: 100px solid #FBFAE2;
    margin-top: 80px;
  }
</style>
```






# Battle #28 - Revert

## #171 - Pumpkin

[Link to the problem](https://cssbattle.dev/play/171)

![target](https://cssbattle.dev/targets/171.png)

```html
<p></p>
<div></div>
<div></div>
<div id="center"></div>
<div id="four"></div>
<div></div>
<style>
  body {
    background: #784972;
    display: grid;
    place-content: center;
    place-items: center;
    grid-template-columns: repeat(5, 40px);
  }
  p {
    position: absolute;
    width: 22px;
    height: 55px;
    background: #F7FFCF;
    border-radius: 11px 11px 0px 0px;
    translate: 0px -72.5px;
    z-index: 3;
  }
  div {
    width: 100px;
    height: 150px;
    background: #F7FFCF;
    margin-top: 50px;
    border-radius: 50%;
    box-shadow: 0px 0px 0px 10px #784972;
  }
  #center {
    z-index: 2;
  }
  #four {
    z-index: 1;
  }
</style>
```


# Battle #28 - Revert

## #172 - Crossbones

[Link to the problem](https://cssbattle.dev/play/172)

![target](https://cssbattle.dev/targets/172.png)

```html
<div></div>
<div id="a"></div>
<style>
  body {
    background: #EFEB99;
    display: grid;
    place-items: center;
  }
  div {
    width: 190px;
    height: 30px;
    background: #8647E6;
    position: absolute;
    rotate: 45deg;
  }
  #a {
    rotate: -45deg;
  }
  div:before, div:after {
    content: "";
    display: block;
    width: 30px;
    height: 30px;
    background: #8647E6;
    border-radius: 50%;
    translate: -15px -15px;
    box-shadow: 190px 0px #8647E6;
  }
</style>
```

# Battle #28 - Revert

## #173 - Hockey Mask

[Link to the problem](https://cssbattle.dev/play/173)

![target](https://cssbattle.dev/targets/173.png)

```html
<div>
  <p></p>
  <p></p>
  <p id="one"></p>
  <p id="eye1"></p>
  <p id="eye2"></p>
  <p></p>
  <p></p>
  <p></p>
  <p></p>
  <p></p>
  <p></p>
</div>
<style>
  body {
    background: #A5B5B4;
  }
  body, div {
    display: grid;
    place-content: center;
  }
  div {
    width: 150px;
    height: 170px;
    background: #FFFFFF;
    padding-bottom: 10px;
    border-radius: 50%;
    place-items: center;
    gap: 10px 0px;
  }
  p {
    margin: 0px;
    width: 10px;
    height: 10px;
    background: #000000;
    border-radius: 50px;
  }
  #one {
    grid-column: span 2;
  }
  #eye1, #eye2 {
    width: 30px;
    height: 30px;
    translate: -20px -10px;
  }
  #eye2 {
    translate: 20px -10px;
  }
</style>
```


# Battle #28 - Revert

## #174 - Witch's Hat

[Link to the problem](https://cssbattle.dev/play/174)

![target](https://cssbattle.dev/targets/174.png)

```html
<div id="crown"></div>
<div id="brim">
  <div></div>
</div>
<div id="yellow"></div>
<style>
  body {
    background: #F4DCBF;
    display: grid;
    place-items: center;
    place-content: center;
    grid-template-rows: 140px 50px;
  }
  div {
    background: #30383F;
  }
  #crown {
    border-left: 44px solid #F4DCBF;
    border-right: 44px solid #F4DCBF;
    border-bottom: 150px solid #30383F;
  }
  #brim, #brim > div {
    height: 60px;
    width: 150px;
    border-radius: 50%;
    overflow: hidden;
  }
  #brim > div {
    border: 10px solid #556D7F;
    translate: -10px -45px;
  }
  #yellow {
    width: 30px;
    height: 20px;
    background: #FBD038;
    position: absolute;
    translate: 0px 70px;
    border-radius: 5px;
  }
</style>
```


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


# Battle #28 - Revert

## #177 - Frankenstein

[Link to the problem](https://cssbattle.dev/play/177)

![target](https://cssbattle.dev/targets/177.png)

```html
<div id="bolts"></div>
<div id="head">
  <div id="hair"></div>
  <div id="eye1"></div>
  <div id="eye2"></div>
  <div id="mouth"></div>
</div>
<style>
  body {
    background: #3C8D3F;
  }
  body, #head {
    display: grid;
    place-items: center;
  }
  #bolts, #eye1, #eye2, #mouth {
    position: absolute;
  }
  #bolts {
    width: 180px;
    height: 10px;
    background: #1A1D2F;
    margin-top: 20px;
    z-index: -1;
  }
  #bolts:before {
    content: "";
    display: block;
    width: 10px;
    height: 30px;
    background: #1A1D2F;
    border-radius: 5px;
    translate: -10px -10px;
    box-shadow: 190px 0px #1A1D2F;
  }
  #head {
    width: 150px;
    height: 150px;
    background: #14F078;
    border-radius: 10px 10px 75px 75px;
    overflow: hidden;
  }
  #head > #hair {
    height: 45px;
    width: 100%;
    background: #1A1D2F;
    align-self: start;
    clip-path: polygon(0 0, 100% 0, 100% 67%, 90% 100%, 80% 67%, 70% 100%, 60% 67%, 50% 100%, 40% 67%, 30% 100%, 20% 67%, 10% 100%, 0 67%);
  }
  #eye1, #eye2 {
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background: radial-gradient(#FFFFFF 5px, #1A1D2F 0);
    translate: -30px 10px;
  }
  #eye2 {
    translate: 30px 10px;
  }
  #mouth {
    width: 40px;
    height: 20px;
    background: #1A1D2F;
    border-radius: 0px 0px 20px 20px;
    translate: 0px 45px;
  }
</style>
```


# Battle #28 - Revert

## #178 - Candy

[Link to the problem](https://cssbattle.dev/play/178)

![target](https://cssbattle.dev/targets/178.png)

```html
<div id="left"></div>
<div id="center">
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>
<div id="right"></div>
<style>
  body {
    background: #CBE8DD;
  }
  body, div {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px
  }
  #center {
    width: 180px;
    height: 100px;
    background: #007192;
    border-radius: 10px;
  }
  #center > div {
    width: 10px;
    height: 110px;
    background: #CBE8DD;
    rotate: 20deg;
  }
  #left, #right {
    width: 30px;
    height: 80px;
    background: #007192;
    clip-path: polygon(0 0, 100% 37.5%, 100% 62.5%, 0 100%);
  }
  #right {
    rotate: 180deg;
  }
</style>
```






# Battle #29 - Font

## #179 - Tanzania

[Link to the problem](https://cssbattle.dev/play/179)

![target](https://cssbattle.dev/targets/179.png)

```html
<style>
  body {background: linear-gradient(150deg, #14A84A 160px, #F8CD1E 160px 180px, #000000 180px 280px, #F8CD1E 280px 300px, #3B66B0 0);}
</style>

```


# Battle #29 - Font

## #180 - Kuwait

[Link to the problem](https://cssbattle.dev/play/180)

![target](https://cssbattle.dev/targets/180.png)

```html
<div></div>
<style>
  body {margin: 0px;
    background: linear-gradient(#13AA4B 33.3%, #FFFFFF 33.3% 66.7%, #EC1E25 0%);}
  div {
    height: 100px;
    border-bottom: 100px solid transparent;
    border-top: 100px solid transparent;
    border-left: 120px solid;
  }
</style>

```


# Battle #29 - Font

## #181 - Iceland

[Link to the problem](https://cssbattle.dev/play/181)

![target](https://cssbattle.dev/targets/181.png)

```html
<div></div>
<div long></div>
<div></div>
<div long></div>
<style>
  body {
    background: #DE3832;
    margin: 0px;
    display: flex;
    gap: 80px;
    flex-wrap: wrap;
  }
  div {
    width: 110px;
    height: 110px;
    background: #33499F;
    box-shadow: 0px 0px 0px 15px #FFFFFF;
  }
  [long] {
    width: 210px;
  }
</style>

```


# Battle #29 - Font

## #182 - Bahrain

[Link to the problem](https://cssbattle.dev/play/182)

![target](https://cssbattle.dev/targets/182.png)

```html
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body {
    background: #DA291C;
    margin: 0px;
  }
  div {
    width: 160px;
    height: 50px;
    background: #FFFFFF;
    clip-path: polygon(0 0, 62.5% 0, 100% 50%, 62.5% 100%, 0 100%);
  }
</style>
```


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
