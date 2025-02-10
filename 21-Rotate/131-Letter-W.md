# Battle #21 - Rotate

## #131 - Letter W

[Link to the problem](https://cssbattle.dev/play/131)

![target](https://cssbattle.dev/targets/131.png)


```html
<div></div>
<div></div>
<div id="white"></div>
<p></p>
<p id="uWhite"></p>
<style>
  body {
    background: #E38F66;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 60px;
  }
  p {
    position: absolute;
    border: 30px solid #62306D;
    width: 60px;
    height: 60px;
    border-radius: 60px;
    translate: -44.9px 20px;
    clip-path: polygon(0 50%, 100% 50%, 100% 100%, 0% 100%);
  }
  #uWhite {
    border-color: #FFFBDA;
    translate: 45px 20px;
    z-index: -1;
  }
  div {
    width: 30px;
    height: 120px;
    background: #62306D;
    border-radius: 15px;
    translate: 0px -20px;
  }
  #white {
    background: #FFFBDA;
  }
</style>
```
