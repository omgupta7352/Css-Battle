# Battle #22 -Grid

## #133 - Spiral

[Link to the problem](https://cssbattle.dev/play/133)

![target](https://cssbattle.dev/targets/133.png)

```html
<<div id="inner"></div>
<div id="two"></div>
<div id="three"></div>
<div id="outer"></div>
<p></p>
<style>
  body {
    background: #F5D6B4;
    display: grid;
    place-items: center;
  }
  p {
    position: absolute;
    width: 20px;
    height: 20px;
    background: #D86F45;
    border-radius: 50px;
    translate: -110px;
    box-shadow: 80px 0px #D86F45;
  }
  div {
    position: absolute;
    border: 20px solid #D86F45;
    border-top: none;
    border-radius: 0px 0px 100px 100px;
  }
  #inner {
    width: 40px;
    height: 22px;
    rotate: 180deg;
    translate: 0px -19px;
  }
  #two {
    width: 80px;
    height: 40px;
    translate: -20px 30px;
  }
  #three {
    width: 120px;
    height: 60px;
    rotate: 180deg;
    translate: 0px -40px;
  }
  #outer {
    width: 160px;
    height: 80px;
    translate: -20px 50px;
  }
</style>
```
