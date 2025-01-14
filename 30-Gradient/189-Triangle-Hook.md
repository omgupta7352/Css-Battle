# Battle #30 - Gradient

## #189 - Triangle Hook

[Link to the problem](https://cssbattle.dev/play/189)

![target](https://cssbattle.dev/targets/189.png)

```html
<div l></div><div m></div><div r>
<style>
  body {
    background: #D669EC;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    background: #FDFBF8;
  }
  [l]{
    border-top: 40px solid #D669EC;
    border-bottom: 40px solid #D669EC; 
    border-right:80px solid #FDFBF8;
    clip-path: polygon(0 0, 100% 0, 100% 18%, 40% 50%, 100% 82%, 100% 100%, 0 100%);
    margin-right: 30px;

  }
  [m]{
    width: 230px;
    height: 20px;
    position: absolute;
  }
  [r]{width:180;
    height: 180px;
    background: linear-gradient(to right, #FDFBF8 110px, #D669EC 110px 130px, #FDFBF8 0);
    clip-path:polygon(0 0,100% 50%,0 100%);
}
</style>
```
