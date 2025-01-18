# Battle #18 - Float

## #108 - Clow Card

[Link to the problem](https://cssbattle.dev/play/108)

![target](https://cssbattle.dev/targets/108.png)

```html
<div id="outer">
  <div id="darkLong">
    <div id="centerCircle">
      <div id="middleCircle">
        <div id="outerCircle"></div>
      </div>
    </div>
  </div>
</div>
<style>
  body {
    background: #000000;
  }
  body, div {
    display: grid;
    place-content: center;
  }
  #outer {
    width: 300px;
    height: 150px;
    background: linear-gradient(105deg, #E96A23 120px, #EBAE11 120px 170px, #E96A23 170px 184px, #EBAE11 184px 209px, #E96A23 209px);
  }
  #darkLong {
    width: 240px;
    height: 120px;
    background: #000000;
    border-radius: 12.5px;
  }
  #centerCircle {
    width: 270px;
    height: 90px;
    background: radial-gradient(circle, #EBAE11 25px, #000000 21px);
    border-radius: 12.5px;
  }
  #middleCircle, #outerCircle {
    width: 120px;
    height: 60px;
    border: 5px solid #EBAE11;
    border-radius: 50%;
  }
  #outerCircle {
    width: 200px;
    height: 80px;
  }
</style>
```
