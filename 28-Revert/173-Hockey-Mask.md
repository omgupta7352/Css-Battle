# Battle #28 - Revert

## #173 - Hockey Mask

[Link to the problem](https://cssbattle.dev/play/173)

![target](https://cssbattle.dev/targets/173.png)

```html
<div>
  <p></p>
  <p></p>
  <p id="one"></p>
  <p id="eye1"></p>
  <p id="eye2"></p>
  <p></p>
  <p></p>
  <p></p>
  <p></p>
  <p></p>
  <p></p>
</div>
<style>
  body {
    background: #A5B5B4;
  }
  body, div {
    display: grid;
    place-content: center;
  }
  div {
    width: 150px;
    height: 170px;
    background: #FFFFFF;
    padding-bottom: 10px;
    border-radius: 50%;
    place-items: center;
    gap: 10px 0px;
  }
  p {
    margin: 0px;
    width: 10px;
    height: 10px;
    background: #000000;
    border-radius: 50px;
  }
  #one {
    grid-column: span 2;
  }
  #eye1, #eye2 {
    width: 30px;
    height: 30px;
    translate: -20px -10px;
  }
  #eye2 {
    translate: 20px -10px;
  }
</style>
```
