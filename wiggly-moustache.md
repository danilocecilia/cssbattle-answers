# [Target #12 - Wiggly Moustache](https://cssbattle.dev/play/12)

![](https://cssbattle.dev/targets/12.png)

```HTML
<div class="semi-circle"></div>
<div class="a"></div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #F5D6B4;
    margin-bottom: 58px;
  }
  .semi-circle {
    display: flex;
    width: 60px;
    height: 30px;
    border-radius: 50px 50px 0 0;
    border: 20px solid #D86F45;
    border-bottom: 0;
    position: relative;
  }
  .semi-circle::before,
  .semi-circle::after {
    content: "";
    width: 60px;
    height: 30px;
    position: absolute;
    border-radius: 0 0 50px 50px;
  }
  .semi-circle::before {
    top: 30;
    left: -100;

    border: 20px solid #D86F45;
    border-top: 0;
  }
  .semi-circle::after {
    top: 30;
    left: 60;
    border: 20px solid #D86F45;
    border-top: 0;
  }
  .a {
    display: flex;
    position: absolute;
    width: 4px;
    height: 0px;
    left: 70px;
    top: 140px;
    border-radius: 10px 10px 0 0;
    border: 8px solid #D86F45;
  }
  .a::after {
    content: "";
    display: flex;
    position: absolute;
    width: 4px;
    height: 0px;
    left: 232px;
    top: -8px;
    border-radius: 10px 10px 0 0;
    border: 8px solid #D86F45;
  }
</style>
```
