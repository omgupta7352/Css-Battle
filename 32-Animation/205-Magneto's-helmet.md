# Battle #32 - Animation

## #205 - Magneto's helmet

[Link to the problem](https://cssbattle.dev/play/205)

![target](https://cssbattle.dev/targets/205.png)

```html
<a><b>
    <c></c>
    <d></d>
  </b></a>
<style>
  * {
    background: #232323;
  }

  body {
    * {
      position: fixed;
    }

    border:solid#AF3A3A;
    border-width:50 45 0 45;
    border-radius:80px 80px 0 0;
    margin:34 120 52;
  }

  a,
  b {
    padding: 14 34;
    border-radius: 50%;
    margin: -48 -34;
  }

  a {
    padding: 35 60;
    margin: 3 -25;
  }

  b,
  c,
  d {
    background: #AF3A3A
  }

  c,
  d {
    padding: 12 26.5;
    margin: 160-79;
    clip-path: polygon(100%0, 0%0, 68% 100%);
  }

  d {
    margin: 160 26;
    scale: -1+1;
  }
</style>


```
