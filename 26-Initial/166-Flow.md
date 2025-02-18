## #166 - Flow

[Link to the problem](https://cssbattle.dev/play/166)

![target](https://cssbattle.dev/targets/166.png)


```html
<div></div>
<div class="orange"></div>
<div id="middleTop"></div>
<div class="orange"></div>
<div></div>
<div id="leftCircle"></div>
<div id="middleCircle"></div>
<div id="rightCircle"></div>
<div id="halfCircle"></div>
<style>
  body {
    background: #D86F45;
    margin: 0px 100px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  div {
    width: 30px;
    height: 125px;
    background: #FDFBF8;
    border-radius: 0px 0px 100px 100px;
  }
  #middleTop {
    width: 80px;
    height: 100px;
  }
  .orange {
    height: 185px;
    background: #D86F45;
  }
  #leftCircle, #middleCircle, #rightCircle {
    position: absolute;
    align-self: center;
    height: 30px;
    border-radius: 50%;
    margin-top: 40px;
  }
  #leftCircle {
    translate:-85px;
  }
  #middleCircle {
    width: 80px;
    height: 80px;
  }
  #rightCircle {
    translate: 85px;
  }
  #halfCircle {
    width: 200px;
    height: 100px;
    translate: 0px -23px;
    z-index: -1;
  }
</style>
```

