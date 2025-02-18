# Battle #26 - Initial

## #165 - Pyramid

[Link to the problem](https://cssbattle.dev/play/165)

![target](https://cssbattle.dev/targets/165.png)


```html
<p></p>
<div id="triangle1"></div>
<div id="triangle2"></div>
<style>
  body {
    background: #F0CD48;
    display: grid;
    place-items: center;
  }
  div, p {
    position: absolute;
  }
  #triangle1 {
    border-left: 100px solid transparent;
    border-right: 100px solid transparent;
    border-bottom: 140px solid #F0CD48;
  }
  #triangle2 {
    border-left: 70px solid transparent;
    border-right: 70px solid transparent;
    border-bottom: 100px solid #66284A;
    margin-top: 9px;
  }
  p {
    width: 100px;
    height: 100px;
    background: #66284A;
    border-radius: 50%;
    translate: 0px -70px;
    color: #66284A;
    box-shadow: -100px 140px, 100px 140px;
  }
</style>
```

