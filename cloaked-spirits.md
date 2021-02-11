# [Target #10 - Cloacked Spirits](https://cssbattle.dev/play/10)

![](https://cssbattle.dev/targets/10.png)

```HTML
<div class="content">
  <div class="up-b">
    <div class='inner-circle1'></div>
  </div>
  <div class="bottom-b">
    <div class="inner-circle2"></div>
    <div class="inner-circle3"></div>
  </div>
</div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #62306D;
  }
  .content {
    display: flex;
   	flex-wrap: wrap;
    max-width: 300px;
  }
  .up-b {
    display:flex;
    justify-content: center;
	  width:100%;
    height: auto;
    min-height: 100px;
  }
  .inner-circle1 {
    display: flex;
    align-self:center;
    background: #AA445F;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    box-shadow: 0 0 0 20px #E38F66
  }
  .bottom-b {
    display:flex;
    justify-content: space-between;
    width: 300px;
    height: 100%;
  }
  .inner-circle3,
  .inner-circle2 {
    display: flex;
    background: #E38F66;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    margin: 20px 20px;
    box-shadow: 0 0 0 20px #AA445F
  }
  .inner-circle1::after,
  .inner-circle3::after,
  .inner-circle2::after {
    content: "";
    width: 100px;
    height: 60px;
    background: #F7EC7D;
    box-shadow: 0 50px 0 20px #F7EC7D;
    z-index:-1;
  }
 .inner-circle1::after {
    height: 160px;
  }
</style>
```
