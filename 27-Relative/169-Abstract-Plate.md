# Battle #27 - Relative

## #169 - Abstract Plate

[Link to the problem](https://cssbattle.dev/play/169)

![target](https://cssbattle.dev/targets/169.png)

```html
<p></p><p></p>
<style>
  * {
    background: radial-gradient(circle, #4FA07B 55px, 0, #0D1335 65px, 0, #4FA07B 85px, 0, #0D1335 95px, 0, #4FA07B 115px, 0, #0D1335 125px, 0, #4FA07B);
  }
  body {
    background: #FBFAE2;
    margin: 32px 45px;
    clip-path: polygon(0 0, 0 100%, 50% 59%, 100% 100%, 100% 0, 50% 41%);
  }
  p {
    position: fixed;
    inset: 0;
    clip-path: polygon(55px 34px, 55px 234px, 190px 150px, 166px 134px, 190px 118px);
  }
  p + p {
    scale: -1;
  }
</style>

```
