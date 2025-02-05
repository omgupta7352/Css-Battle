# Battle #18 - Float

## #103 - Super Saiyan

[Link to the problem](https://cssbattle.dev/play/103)

![target](https://cssbattle.dev/targets/103.png)


```html
<b></b>
<r></r>
<style>
  html, body {
    background: #161616;
  }
  *, :before, :after {
    content: "";
    position: fixed;
    background: #EBAE11;
    border-radius: 50%;
  }
  body:before {
    width: 80px;
    height: 57px;
    background: linear-gradient(90deg, #fff 50%, #FFDEB9 0px);
    border-radius: 0px 0px 99px 99px;
    bottom: 84px;
    left: 160px;
  }
  b {
    z-index: -1;
  }
  b:before, b:after {
    width: 60px;
    height: 60px;
    top: 130px;
    left: 141px;
    clip-path: polygon(0px 37%, 100% 65%, 100% 100%, 0px 100%);
  }
  b:after {
    left: 199px;
    clip-path: polygon(0px 65%, 100% 37%, 100% 100%, 0px 100%);
  }
  r:before, r:after {
    width: 60px;
    height: 60px;
    top: 112px;
    left: 155px;
    clip-path: polygon(0px 0px, 21% 0px, 79% 100%, 0px 100%);
  }
  r:after {
    left: 185px;
    clip-path: polygon(21% 100%, 79% 0px, 100% 0%, 100% 100%);
  }
  body:after {
    background: #161616;
    width: 20px;
    height: 10px;
    border-radius: 0px 0px 10px 10px;
    left: 190px;
    bottom: 94px;
    box-shadow: 0px -47px 0px 9px #EBAE11;
  }
  html:before {
    height: 119px;
    width: 119px;
    top: 66px;
    left: 182px;
    clip-path: circle(50% at -23.4px 50%);
  }
</style>
```
