# Battle #14 - ZIndex

## #79. Tambourine

[Link to the problem](https://cssbattle.dev/play/79)

![target](https://cssbattle.dev/targets/79.png)

```html
<div>
  <p></p>
  <p></p>
  <p></p>
  <p></p>
  <p></p>
</div>
<style>
  body {
    background: #6592CF;
    display: grid;
    place-content: center;
  }
  div {
    width: 150px;
    height: 150px;
    border: 10px solid #243D83;
    border-radius: 50%;
    translate: 0px 10px;
  }
  p {
    position: absolute;
    width: 50px;
    height: 50px;
    background: radial-gradient(#243D83 5px, #6592CF 5px 15px, #243D83 15px);
    border-radius: 50%;
    margin: 0px;
    translate: 100% -60%;
  }
  p:nth-of-type(2) {
    translate: -20px 10px;
  }
  p:nth-of-type(3) {
    translate: 120px 10px;
  }
  p:nth-of-type(4) {
    translate: -20px 80px;
  }
  p:nth-of-type(5) {
    translate: 120px 80px;
  }
  div:before, div:after {
    position: absolute;
    display: block;
    content: "";
  }
  div:before {
    background: #243D83;
    height: 70px;
    width: 70px;
    border-radius: 10px 70px;
    translate: 58% 149%;
    rotate: 135deg;
  }
  div:after {
    background: #6592CF;
    border-radius: 50%;
    height: 100px;
    width: 100px;
    translate: 25% 125.5%;
  }
</style>
```
