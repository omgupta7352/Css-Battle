# Battle #22 - Grid

## #135 - Spikes

[Link to the problem](https://cssbattle.dev/play/135)

![target](https://cssbattle.dev/targets/135.png)

```html
<div></div>
<div id="topRight"></div>
<div id="bottomLeft"></div>
<div id="bottomRight"></div>
<style>
  body {
    background: #E3516E;
    display: grid;
    place-content: center;
    grid-template-columns: auto auto;
    gap: 20px;
  }
  div {
    width: 70px;
    height: 40px;
    background: #D9D9D9;
    border-radius: 0px 20px 20px 0px;
    clip-path: polygon(0 0, 100% 0, 100% 100%, 56% 100%);
  }
  #topRight {
    scale: -1 1;
  }
  #bottomLeft {
    scale: 1 -1;
  }
  #bottomRight {
    rotate: 180deg;
  }
</style>
```
