# Battle #22 - Grid

## #140 - Eclipse

[Link to the problem](https://cssbattle.dev/play/140)

![target](https://cssbattle.dev/targets/140.png)

```html
<div id="moon"></div>
<div id="pyramid"></div>
<style>
  body {
    background: #4F77FF;
    display: grid;
    justify-items: center;
    align-content: end;
    margin: 0px;
  }
  #moon {
    width: 80px;
    height: 80px;
    background: radial-gradient(circle at 50% 100%, #4F77FF 40px, #FFFFFF 40px);
    border-radius: 50%;
    margin-bottom: 8px;
  }
  #pyramid {
    border-bottom: 162.5px solid #1038BF;
    border-left: 162.5px solid transparent;
    border-right: 162.5px solid transparent;
  }
</style>
```
