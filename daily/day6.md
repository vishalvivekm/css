<img src="https://github.com/vishalvivekm/css/assets/110674407/beee1af8-b231-4e03-a648-8fb9ac5d71e6" width="640px" height="400px" alt="target">

```css
<style>
  * {
    background: #EA6B62;
  }
  body {
    margin: 0 0;
    height: 150px;
    background: linear-gradient(90deg,#512B2A 37.5%, #EA6B62 37.5% 62.5%, #512B2A 62.5% );
  }
</style>
```


```css
<!-- second approach -->
<div></div>
<style>
  body {
    height: 100vh;
    background: linear-gradient(90deg,#512B2A 37.5%, #EA6B62 37.5% 62.5%, #512B2A 62.5% );
  }
  div {
    position:absolute;
    bottom: 0;
    left:0;
    right: 0;
    height: 150px;
    background: #EA6B62;
  }
</style>
```

```css
<!-- third approach  -->

<style>
  * {
   background: #EA6B62;
    >* {
      height: 150px;
      background: #512B2A;
      margin: 0 250 150 0;
      box-shadow: 250px 0 #512B2A;
    }
  }
</style>

```



