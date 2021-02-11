# [Target #4 - Ups and Downs](https://cssbattle.dev/play/4)

![](https://cssbattle.dev/targets/4.png)

```HTML
<div class="content">
	<div class="up"></div>
  	<div class="up"></div>
   	<div class="up"></div>
  	<div class="down"></div>
    <div class="down"></div>
    <div class="down"></div>
</div>
<style>
  body{
    background: #62306D;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .content {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    width: 300px;
    height: 200px;
  }
  .down{
    display: flex;
    width: 100px;
    height: 100px;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    background: #F7EC7D;
  }
  .up {
    display: flex;
    width: 100px;
    height: 100px;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
    background: #F7EC7D;
  }
  .up:nth-of-type(odd),
  .down:nth-of-type(odd){
    background: none;
  }
</style>
```
