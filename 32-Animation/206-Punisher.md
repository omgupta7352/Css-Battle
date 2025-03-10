# Battle #32 - Animation

## #206 - Punisher

[Link to the problem](https://cssbattle.dev/play/206)

![target](https://cssbattle.dev/targets/206.png)

```html
<a><b></b>
  <c></c>
  <d>
</a>
<e></e>
<f></f>
<style>
  * {
    * {
      position: fixed;
    }
    background:#CAE5DC;
  }

  a,
  e,
  f {
    background: #000;
  }

  a {
    padding: 70;
    border-radius: 50%;
    margin: 32 122;
  }

  b,
  c {
    background: linear-gradient(#000 50%, #CAE5DC 0);
    padding: 22.5;
    border-radius: 50%;
    rotate: -28deg;
    margin: -12 10;
  }

  c {
    rotate: 28deg;
    margin: -12 -55;
  }

  d {
    padding: 15 10;
    margin: 26-10;
    clip-path: polygon(50%0%, 0%100%, 100%100%);
  }

  e,
  f {
    padding: 10 50;
    margin: 152 142;
    z-index: -1;
  }

  f {
    padding: 55.5 8;
    margin: 154;
    box-shadow: 20px 0, 40px 0, 60px 0;
  }
</style>

```
