# Battle #22 - Grid

## #136 - Alien Eye

[Link to the problem](https://cssbattle.dev/play/136)

![target](https://cssbattle.dev/targets/136.png)


```html
<div>
  <div yellow>
    <div inner></div>
  </div>
</div>
<style>
  * {
    background: radial-gradient(circle, #FCBE5C 90px, #998235 90px);
  }
  body, div {
    display: grid;
    place-content: center;
  }
  div {
    width: 140px;
    height: 140px;
    background: #0B2429;
    border-radius: 50%;
    translate: 10px;
  }
  [inner] {
    width: 60px;
    height: 60px;
    background: #998235;
  }
  [yellow] {
    width: 100px;
    height: 100px;
    background: #FCBE5C;
    translate: -10px;
  }
</style>
```
