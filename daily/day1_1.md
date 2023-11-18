**566.9(98.4% match)**
![Screenshot from 2023-11-17 20-10-05](https://github.com/vishalvivekm/css/assets/110674407/d25d5cf7-af4f-42c0-acf6-f5debba6fd2b)

```
// first go
<div class="parent"><div class="triangle"></div><div class="rectangle"></div><div class="line"></div></div>
<style>
  * {
    background: #5B8395;
  }
  .parent {
    display:flex;
    flex-direction: column;
    justify-content: center;
    align-items:center;
  }
.triangle {
  background: #F1FAFE;
  border-bottom: 179px solid #F1FAFE;
  border-left: 90px solid #5B8395;
  border-right: 90px solid #5B8395;
  width: 0px;
  height: 32px;
}
  .rectangle {
    background-color: #F1FAFE; 
    height: 89px;
    width: 40px;
  }
  .line {
    position: absolute;
    width: 100%;
    height: 38px;
    background-color: #5B8395;
  }
</style>
```
