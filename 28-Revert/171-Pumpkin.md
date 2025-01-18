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
