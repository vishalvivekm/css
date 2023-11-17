<div class="parent"><div class="child"></div><div class="circle"></div></div>
<style>
  .parent{
    background: #7D4886;
    width: 100%;
    height: 100%;
    display:grid;
    place-items: center;
  }
  .child {
    width: 150px;
    height: 150px;
    background: #670053;
    transform: rotate(45deg);
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .circle {
    height: 100px;
    width: 100px;
    background: #7D4886;
    border-radius: 50%;
    position: absolute;
  }
</style>
