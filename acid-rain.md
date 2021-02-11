# [Target #5 - Acid Rain](https://cssbattle.dev/play/5)

![](https://cssbattle.dev/targets/5.png)

```HTML
<div class="c"></div>
<style>
  <div class="content">
  <div class="middle-drop"></div>
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

  .content {
    display: flex;
    justify-content: center;
    width: 90%;
    height: 80%;
    z-index: 0;
  }

  .middle-drop {
    align-self: center;
    position: relative;
    width: 120px;
    height: 120px;
    border-bottom-left-radius: 70px;
    border-bottom-right-radius: 70px;
    border-top-left-radius: 70px;
    background: #998235;
  }

  .middle-drop::after {
    content: "";
    top: 60px;
    bottom: 0;
    left: -60px;
    right: 0;
    width: 120px;
    height: 120px;
    border-bottom-left-radius: 70px;
    border-bottom-right-radius: 70px;
    border-top-left-radius: 70px;
    background: #F3AC3C;
    position: absolute;
    z-index: 1;  /* to be below the parent element */
  }

  .middle-drop::before {
    content: "";
    top: -60px;
    bottom: 0;
    left: 60px;
    right: 0;
    width: 120px;
    height: 120px;
    border-radius: 50%;
    background: #F3AC3C;
    position: absolute;
    z-index: -1;  /* to be below the parent element */
  }
</style>
```
