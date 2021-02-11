# [Target #11 - Eye of Sauron](https://cssbattle.dev/play/11)

![](https://cssbattle.dev/targets/11.png)

```HTML
<div class="sm-circle"></div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #191210
  }
  .sm-circle {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #84271C;
    box-shadow: 0 0 0 25px #191210,
      			    0 0 0 45px #ECA03D;
    position: relative
  }
  .sm-circle::before,
  .sm-circle::after {
    content: "";
	  position: absolute;
    width: 60px;
    height: 30px;
    background: #191210;
    border: 20px solid #ECA03D
  }
  .sm-circle::before {
	  border-radius: 0 0 50px 50px;
    border-top: 0;
    top: 25;
    left: -125
  }
  .sm-circle::after {
	  border-radius: 50px 50px 0 0;
    border-bottom: 0;
    top: -25;
    left: 75
  }
</style>
```
