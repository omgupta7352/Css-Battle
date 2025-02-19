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
