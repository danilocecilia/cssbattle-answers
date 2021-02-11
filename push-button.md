# [Target #3 - Push Button](https://cssbattle.dev/play/3)

![](https://cssbattle.dev/targets/3.png)

```HTML
<div class="c"></div>
<style>
  body{
    display: flex;
    background:#6592CF;
    justify-content: center;
    align-items: center;
  }
  .c{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #EEB850;
    box-shadow: 0 0 0 50px #243D83, 0 0 0 100px #6592CF;
  }
  .c::after {
    content: "";
	position: fixed;
    top: 25%;
    left: 50;
    width: 300;
    height: 150;
    background: #243D83;
    z-index: -1
  }
```
