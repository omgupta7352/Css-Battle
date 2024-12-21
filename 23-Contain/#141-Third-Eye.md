# Battle #23 - Contain

## #141 - Third Eye

[Link to the problem](https://cssbattle.dev/play/141)

![target](https://cssbattle.dev/targets/141.png)

```html
<div></div>
<div center></div>
<div bottomRight></div>
<style>
  body {
    background: #E3516E;
    display: grid;
    margin: 0px;
  }
  div {
    width: 75px;
    height: 75px;
    background: #D9D9D9;
    border-radius: 0px 0px 75px 0px;
  }
  [center] {
    justify-self: center;
    align-self: center;
    width: 100px;
    height: 100px;
    border-radius: 0px 100px;
    rotate: -45deg;
  }
  [bottomRight] {
    justify-self: end;
    align-self: end;
    rotate: 180deg;
  }
</style>
```
