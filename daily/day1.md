```
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
```

![Screenshot from 2023-11-17 20-14-40](https://github.com/vishalvivekm/css/assets/110674407/27287b98-5dd4-4be0-adff-8263b1d2e362)


// alternative soltions:

```
<style>
* {
  background: #7D4886;
  +*{
    width: 150;
    height: 150;
    background: radial-gradient(circle, #7D4886, 53q, #670053 0);
     rotate: 45deg;
    margin: 75px 125px
  }
 
}
  
</style>
```

// 400px x 300px