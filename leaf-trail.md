# [Target #7 - Leaf Trail](https://cssbattle.dev/play/7)

![](https://cssbattle.dev/targets/7.png)

```HTML
<div class="leaf">
</div>
<style>
  body{
    display: flex;
    justify-content: center;
    align-items: center;
    background: #0B2429;
    width: 100%;
    height: 100%;
    background: #0B2429;
    margin: 0;
  }
  .leaf {
    display: flex;
    width: 150px;
    height: 150px;
    border-top-left-radius: 100px;
    border-bottom-right-radius: 100px;
    background: #998235;
    position: relative;
  }
  .leaf::before{
    content: "";
    position: absolute;
    left: -50px;
    width: 150px;
    height: 150px;
    border-top-left-radius: 100px;
    background: #1A4341;
    z-index: -1;
  }
  .leaf::after {
    content: "";
    position: absolute;
    left: 50px;
    width: 150px;
    height: 150px;
    border-top-left-radius: 100px;
    border-bottom-right-radius: 100px;
    background: #F3AC3C;
    z-index: 0;
  }
</style>
```
