# Battle #26 - Initial

## #163 - Missing Piece

[Link to the problem](https://cssbattle.dev/play/163)

![target](https://cssbattle.dev/targets/163.png)


```html
<div id="topLeft"></div>
<div></div>
<div></div>
<style>
  body {
    background: #D669EC;
    display: grid;
    place-content: center;
    grid-template-columns: 100px 100px;
    gap: 20px;
  }
  div {
    width: 100px;
    height: 100px;
    background: linear-gradient(135deg, #D669EC 33px, #FDFBF8 33px 108.5px, #D669EC 0px);
  }
  #topLeft {
    rotate: 90deg;
  }
</style>
```

