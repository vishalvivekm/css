> ![Screenshot from 2023-11-18 23-23-55](https://github.com/vishalvivekm/css/assets/110674407/5d7a13e5-8a6b-4c0b-8e77-04050d64259f)

**(96.3% match)**
```
<div class="parent">
  <div class="up"></div>
  <div class="middleContainer">
    <div class="vertical"></div>
    <div class="square"></div>
    <div class="vertical"></div>
  </div>
  <div class="lying up"></div>
</div>

<style>
  * {
    background: #C6DD7F;
  }

  .parent {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 29px;
  }

  .vertical {
    width: 85px;
    height: 80px;
    background: #486841;
    border: 2px solid #486841;
    border-radius: 0px 990px 0px 1000px;
    transform: rotate(45deg);
  }

  .square {
    height: 50px;
    width: 50px;
    background: #486841;
    margin: 0 2px;
  }

  .middleContainer {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .up {
    margin-bottom: -10px;
    width: 85px;
    height: 80px;
    background: #486841;
    border: 2px solid #486841;
    border-radius: 0px 1000px 0px 1000px;
    transform: rotate(-45deg);
  }

  .lying {
    margin-top: -10px;
  }
</style>
```
