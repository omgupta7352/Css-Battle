# Battle #25 - Flex

## #157 - Monopoly

[Link to the problem](https://cssbattle.dev/play/157)

![target](https://cssbattle.dev/targets/157.png)


```html
<div id="crown"></div>
<div id="brim"></div>
<div id="eye"></div>
<div id="monocle"></div>
<div id="mustache1"></div>
<div id="mustache2"></div>
<style>
  body {
    background: #E38F66;
    display: grid;
    place-content: center;
    place-items: center;
    grid-template-columns: 50px 50px;
  }
  div {
    background: #FFFBDA;
  }
  #crown {
    width: 120px;
    height: 90px;
    border-radius: 90px 90px 0px 0px;
  }
  #brim {
    width: 180px;
    height: 20;
    border-radius: 20px;
  }
  #crown, #brim {
    grid-column: span 2;
  }
  #eye, #monocle {
    width: 20px;
    height: 20px;
    border-radius: 50px;
    margin: 22px 0px 28px;
    margin-right: 10px;
  }
  #monocle {
    background: #E38F66;
    box-shadow: 0px 0px 0px 10px #FFFBDA;
    margin-left: 20px;
  }
  #mustache1, #mustache2 {
    width: 40px;
    height: 40px;
    border-radius: 0px 50% 50%;
    rotate: -45deg;
  }
  #mustache2 {
    rotate: 135deg;
  }
</style>
```
