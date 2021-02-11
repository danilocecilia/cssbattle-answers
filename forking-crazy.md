# [Target #8 - Forking Crazy](https://cssbattle.dev/play/8)

![](https://cssbattle.dev/targets/8.png)

```HTML
<div class="wrapper-grips">
  <div class="strips"></div>
  <div class="strips"></div>
  <div class="strips"></div>
  <div class="strips"></div>
</div>
<div class="content"></div>
<div class='base'></div>
<style>
  body{
    display: flex;
    justify-content: flex-end;
    flex-direction: column;
    align-items: center;
    background: #0B2429;
    width: 100%;
    height: 100%;
    background: #6592CF;
    margin: 0
  }
  .wrapper-grips {
    display: flex;
    width: 140px;
    justify-content: space-between
  }
  .strips {
    display: flex;
    align-self: center;
    width: 20px;
    height: 100px;
	  border-radius: 100px 100px 0 0 ;
    background: #060F55
  }

  .strips:nth-of-type(1)::after {
    content: "";
    top: 150px;
    left: 150px;
    position: absolute;
    width: 20px;
    height: 10px;
    border-radius: 0 0 100px 100px;
    background: #6592CF
  }
  .strips:nth-of-type(1)::before {
    content: "";
    top: 150px;
    left: 190px;
    position: absolute;
    width: 20px;
    height: 10px;
	  border-radius: 0 0 100px 100px;
    background: #6592CF
  }
  .strips:nth-of-type(2)::before {
    content: "";
    top: 150px;
    left: 230px;
    position: absolute;
    width: 20px;
    height: 10px;
    border-radius: 0 0 100px 100px;
    background: #6592CF;
  }
  .content {
    display: flex;
    width: 140px;
    height: 100px;
    border-radius: 0 0 100px 100px;
    background: #060F55;
  }
  .base {
    height: 100%;
    width: 20px;
    max-height: 50px;
    background: #060F55;
  }
</style>
```
