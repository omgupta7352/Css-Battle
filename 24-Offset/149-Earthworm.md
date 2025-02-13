# Battle #24 - Offset

## #149 - Earthworm

[Link to the problem](https://cssbattle.dev/play/149)

![target](https://cssbattle.dev/targets/149.png)


```html
<p></p>
<div id="vertical"></div>
<div id="horizontal"></div>
<style>
  body {
    background: #E38F66;
    margin: 100px 0px;
  }
  div {
    width: 120px;
    height: 120px;
    background: #FFFBDA;
    border-radius: 20px;
    box-shadow: 80px 80px #FFFBDA;
  }
  #vertical {
    width: 40px;
  }
  #horizontal {
    height: 40px;
    translate: 0px -100%;
  }
  p {
    position: absolute;
    background: #E38F66;
    width: 50px;
    height: 50px;
    border-radius: 12px;
    translate: 40px 15px;
    box-shadow: -10px 10px #FFFBDA, -10px 88px #E38F66,
      0px 80px #FFFBDA, 80px 80px #E38F66, 70px 95px #FFFBDA;
  }
</style>
```

