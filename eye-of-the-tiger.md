# [Target #16 - Eye of the Tiger](https://cssbattle.dev/play/16)

![](https://cssbattle.dev/targets/16.png)

```HTML
<div class="sm-c">
	<div class="triangle"></div>
</div>

<style>
  body{
    background: #0B2429;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative
  }
  .sm-c {
    display: flex;
    position: relative;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #0B2429;
    box-shadow: 0 0 0 45px #F3AC3C,
      			0 0 0 65px #0B2429,
		        0 0 0 75px #998235
  }
  .triangle {
    position: absolute;
    top: -25;
    left: 46;
    width: 100px;
    height: 100px;
    background: #998235;
	  transform: rotate(45deg);
    z-index: -1;
  }
 .triangle::after {
	  content: "";
    position: absolute;
   	top: 100px;
	  left: -100px;
    width: 100px;
    height: 100px;
    background: #998235;
  }
</style>
```
