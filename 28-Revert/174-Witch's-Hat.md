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
