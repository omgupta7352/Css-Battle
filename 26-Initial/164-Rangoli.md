# Battle #26 - Initial

## #164 - Rangoli

[Link to the problem](https://cssbattle.dev/play/164)

![target](https://cssbattle.dev/targets/164.png)

```html
<div id="yellow"></div>
<div id="orange"></div>
<div id="purple"></div>
<div id="white"></div>
<style>
  body {
    background: #66284A;
    display: grid;
    place-content: center;
    place-items: center;
    grid-template: 50px 70px 50px / 120px 120px;
  }
  div {
    width: 60px;
    height: 60px;
    border: 20px solid #F0CD48;
    border-radius: 50%;
    border-left-color: transparent !important;
    rotate: -45deg;
  }
  #yellow, #white {
    grid-column: span 2;
  }
  #orange {
    rotate: -135deg;
    border-color: #D86F45;
  }
  #white {
    rotate: 135deg;
    border-color: #FDFBF8;
  }
  #purple {
    rotate: 45deg;
    border-color: #D669EC;
  }
</style>
```

