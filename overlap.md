# [Target #15 - Overlap](https://cssbattle.dev/play/15)

![](https://cssbattle.dev/targets/15.png)

```HTML
<div class="r"></div>
<div class="l"></div>
<style>
  body{
    background: #09042A;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative
  }
  .l {
    position: absolute;
    top: 67;
    left: 167px;
    width: 150px;
   	height: 150px;
	  border: 0;
    border-radius: 50%;
    transform: rotate(90deg);
    box-shadow: 0em 100px 0 0 #E78481 inset
  }
  .r {
    position: absolute;
    top: 67;
    left: 67px;
    width: 150px;
   	height: 150px;
	  border: 0;
    border-radius: 50%;
	  transform: rotate(-90deg);
    box-shadow: 0em 100px 0 0 #7B3F61 inset
  }
</style>
```
