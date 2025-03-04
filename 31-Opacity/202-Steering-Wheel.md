# Battle #31 - Opacity

## #202 - Steering Wheel

[Link to the problem](https://cssbattle.dev/play/202)

![target](https://cssbattle.dev/targets/202.png)

```html
<div></div>
<h1></h1>
<style>
  body {
    background: #4f77ff;
  }
  div {
    width: 140px;
    height: 140px;
    background: radial-gradient(circle at center, #4f77ff 10px, #1038bf 10px);
    border-radius: 50%;
    border: solid 30px #1038bf;
    margin: 50 auto;
    position: relative;
    overflow: hidden;
  }
  div::after {
    position: absolute;
    content: "";
    width: 150px;
    height: 70px;
    background: #4f77ff;
    bottom: -12;
    left: -94;
    border-radius: 10px;
    box-shadow: 180px 0 #4f77ff, 90px -100px #4f77ff;
  }
  h1 {
    width: 30px;
    height: 40px;
    background: #4f77ff;
    margin: -250 auto;
    position: relative;
  }
</style>
```
