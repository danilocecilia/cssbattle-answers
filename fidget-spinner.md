# [Target #17 - Fidget Spinner](https://cssbattle.dev/play/17)

![](https://cssbattle.dev/targets/17.png)

```HTML
<div class='w1'>
  <div class='c1'></div>
  <div class='c2'></div>
</div>
<div class='w2'>
  <div class='c11'></div>
  <div class='c22'></div>
</div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #09042A;
  }
  .w1 {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 180px;
    height: 100px;
    background: #09042A;
  }
  .c1,
  .c2,
  .c11,
  .c22 {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: #09042A;
	  box-shadow: 0 0 0 10px #E78481
  }
  .top {
    flex-basis: 100%;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: #09042A;
	  box-shadow: 0 0 0 10px #E78481
  }
  .w2 {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    position: absolute;
    background: #E78481;
    border-radius: 50%;
    height: 166px
  }
  .c11,
  .c22 {
    background: #F5BB9C;
    box-shadow: 0 0 0 10px #09042A
  }
</style>
```
