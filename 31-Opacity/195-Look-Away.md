# Battle #31 - Opacity

## #195 - Look Away

[Link to the problem](https://cssbattle.dev/play/195)

![target](https://cssbattle.dev/targets/195.png)

```html
<div></div>
<h1></h1>
<h1 a></h1>
<h2></h2>
<style>
  body {
    background: #131313;
  }
  div {
    width: 240px;
    height: 190px;
    background: radial-gradient(
        circle at 20px 105px,
        #f459e3 150px,
        transparent 100px
      ), radial-gradient(1Q at 70px 110px, #e89a52 140px, #f9c96c 100px);
    margin: 55 auto;
    rotate: -15deg;
    border-radius: 65px 65px 120px 120px;
  }
  h1 {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    margin: -180 92;
    position: relative;
    border: solid 15px #131313;
    clip-path: polygon(0 50%, 100% 50%, 100% 100%, 0 100%);
  }
  [a] {
    margin: 100 187;
  }
  h2 {
    width: 15px;
    height: 15px;
    border-radius: 50%;
    background: #131313;
    position: relative;
    margin: -148 92;
    color: #131313;
    box-shadow: 65px 0, 95px 0, 160px 0;
  }
</style>
```
