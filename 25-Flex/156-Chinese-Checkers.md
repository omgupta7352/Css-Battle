# Battle #25 - Flex

## #156 - Chinese Checkers

[Link to the problem](https://cssbattle.dev/play/156)

![target](https://cssbattle.dev/targets/156.png)

```html
<div></div>
<p></p>
<style>
  body {
    background: #926927;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 220px;
    background: radial-gradient(
        circle at 10px 10px,
        #f8b140 10px,
        transparent 10px
      ), radial-gradient(circle at 10px 10px, #f8b140 10px, transparent 10px);
    background-size: 30px 50px, 30px 50px;
    background-position: 0 0px, 15px 25px;
  }
  p {
    width: 100px;
    height: 25px;
    position: fixed;
    background: #926927;
    top: 20;
    left: 90;
    box-shadow: 0 200px 0 0 #926927, 130px 0 0 0 #926927,
      130px 200px 0 0 #926927, -20px 25px 0 0 #926927, -20px 175px 0 0 #926927, 140px
        25px 0 0 #926927, 140px 175px 0 0 #926927, -80px 75px 0 0 #926927,
      200px 75px 0 0 #926927, -60px 102px 0 0 #926927, 190px 102px 0 0 #926927, -80px
        129px 0 0 #926927, 200px 129px 0 0 #926927;
  }
</style>
```

