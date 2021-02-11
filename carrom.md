# [Target #2 - Carrom](https://cssbattle.dev/play/2)

![](https://cssbattle.dev/targets/2.png)

```HTML
<div class="wrapper">
  <div class="top">
    <div class="block"></div>
    <div class="block"></div>
  </div>
  <div class="bottom">
    <div class="block"></div>
    <div class="block"></div>
  </div>
</div>
<style>
  body {
    display: flex;
    background: #62374e;
  }
  .wrapper {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 100%;
    height: auto;
    margin: 42px;
  }
  .bottom,
  .top {
    display: flex;
    justify-content: space-between;
    width: 100%;
  }
  .block {
    width: 50px;
    height: 50px;
    background: #fdc57b;
  }
</style>
```
