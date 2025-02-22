# Battle #29 - Font

## #184 - India

[Link to the problem](https://cssbattle.dev/play/184)

![target](https://cssbattle.dev/targets/184.png)


```html
<div id="circle"></div>
<div></div>
<div id="a"></div>
<div id="b"></div>
<style>
  body {
    background: linear-gradient(#F19E4B 100px, #FFFFFF 100px 200px, #3F8627 0);
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
    width: 4px;
    height: 70px;
    background: #00007B;
  }
  #a {
    rotate: 60deg;
  }
  #b {
    rotate: 120deg;
  }
  #circle {
    width: 80px;
    height: 80px;
    background: radial-gradient(#00007B 10px, #FFFFFF 10px 30px, #00007B 0);
    border-radius: 50%;
  }
</style>
```
