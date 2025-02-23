# Battle #29 - Font

## #186 - Guernsey

[Link to the problem](https://cssbattle.dev/play/186)

![target](https://cssbattle.dev/targets/186.png)


```html
<div id="redVertical"></div>
<div id="redHorizontal"></div>
<div id="yellowVertical"></div>
<div id="yellowHorizontal"></div>
<style>
  body {
    display: grid;
    place-items: center;
    margin: 0px;
  }
  #redVertical, #redHorizontal {
    width: 80px;
    height: 400px;
    background: #E8112D;
  }
  div {
    position: absolute;
  }
  #yellowVertical, #yellowHorizontal {
    width: 20px;
    height: 230px;
    background: #F9DD16;
  }
  #yellowHorizontal, #redHorizontal {
    rotate: 90deg;
  }
  #yellowVertical:before, #yellowVertical:after, #yellowHorizontal:before, #yellowHorizontal:after {
    content: "";
    display: block;
    border-left: 20px solid transparent;
    border-right: 20px solid transparent;
    border-top: 30px solid #F9DD16;
    translate: -10px;
  }
  #yellowVertical:after, #yellowHorizontal:after {
    translate: -10px 170px;
    rotate: 180deg;
  }
</style>
```

