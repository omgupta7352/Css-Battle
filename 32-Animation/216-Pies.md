# Battle #33 - Outline

## #216 - Pies

[Link to the problem](https://cssbattle.dev/play/216)

![target](https://cssbattle.dev/targets/216.png)

```html

<a><a></a></a>
<style>
  * {
    background: #37212D;
  }

  a {
    --a: #BCE6E9;
    --b: #EE9B99;
    --c: #76608A;
    position: fixed;
    padding: 60;
    background: radial-gradient(1q at 50%100%, var(--a) 60px, #0000), radial-gradient(1q at 100%100%, var(--b) 120px, var(--c));
    margin: 82 72;
  }

  a+a {
    --a: #76608A;
    --b: #BCE6E9;
    --c: #EE9B99;
    rotate: 90deg;
    margin: 82 192;
  }
</style>

```
