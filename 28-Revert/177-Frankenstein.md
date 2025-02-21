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
