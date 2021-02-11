# [Target #6 - Missing Slice](https://cssbattle.dev/play/6)

![](https://cssbattle.dev/targets/6.png)

```HTML
<div class="content">
  	<div></div>
    <div></div>
    <div></div>
  	<div></div>
</div>
<style>
  body{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
    background: #E3516E;
    margin: 0;
  }
  .content {
    display: flex;
    flex-wrap: wrap;
    width: 50%;
    height: 200px;
  }
  div:nth-of-type(2) {
    display: flex;
    width: 100px;
    height: 100px;
    border-top-left-radius: 100%;
    background: #51B5A9;
  }
  div:nth-of-type(3) {
    display: flex;
    width: 100px;
    height: 100px;
    border-top-right-radius: 100%;
    background: #FADE8B;
  }
  div:nth-of-type(4) {
    display: flex;
    width: 100px;
    height: 100px;
    border-bottom-left-radius: 100%;
    background: #F7F3D7;
  }
</style>
```
