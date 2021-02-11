# [Target #14 - Web Marker Logo](https://cssbattle.dev/play/14)

![](https://cssbattle.dev/targets/14.png)

```HTML
<div class="left"></div>
<div class="right"></div>
<style>
  body{
    background: #F2F2B6;
    display: flex;
    align-items: center;
    position: relative
  }
  .left {
    position: absolute;
	  left: 52;
    border-top: 130px solid #ff6d00;
    border-right: 75px solid transparent;
    border-left: 75px solid transparent
  }
  .left::after {
    content: "";
    position: absolute;
	  bottom: 0;
	  left: -55;
    border-top: 130px solid #FD4602;
    border-right: 75px solid transparent;
    border-left: 75px solid transparent;
    z-index: -1
  }
  .right {
    position: absolute;
	  right: 72;
    border-bottom: 130px solid #FD4602;
    border-right: 75px solid transparent;
    border-left: 75px solid transparent
  }
  .right::after {
    content: "";
    position: absolute;
	  right: -95;
    border-bottom: 130px solid #FF6D00;
    border-right: 75px solid transparent;
    border-left: 75px solid transparent;
    z-index: -1
  }
</style>
```
