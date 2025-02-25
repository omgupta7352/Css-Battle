# Battle #30 - Gradient

## #190 - Power Chip

[Link to the problem](https://cssbattle.dev/play/190)

![target](https://cssbattle.dev/targets/190.png)


```html
<div></div>
<div id="right">
<style>
  body {
    background: #E3516E;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
  }
  div {
    width: 130px;
    height: 150px;
    background: #FADE8B;
    display: grid;
    justify-items: center;
    align-content: end;
    clip-path: polygon(0 0, 67% 0, 100% 46%, 100% 100%, 0 100%);
  }
  #right {
    clip-path: polygon(0 46%, 33% 0, 100% 0, 100% 100%, 0 100%);
  }div:before,div:after {content:"";display:block}
  div:before{
    border-left: 25px solid #FADE8B;
    border-right: 25px solid #FADE8B;
    border-bottom: 40px solid #E3516E}
  div:after{background:#E3516E;
    width:20px;
    height:50px; }
</style>
```

