
> ![Screenshot from 2024-01-02 11-07-28](https://github.com/vishalvivekm/css/assets/110674407/8b6e390d-5bdb-4540-bde1-9b87a6065a4d)
<br>**100% Match**

<div class="container">
  <div class="bar"></div>
  <div class="middle">
    <div class="bar vertical"></div>
    <div class="square"></div>
    <div class="bar vertical"></div>
  </div>
  <div class="bar"></div>
</div>
<style>
.vertical {
  transform: rotate(90deg);
  align-self:center;
}
.middle {
  display:flex;
}
.square {
  height: 120px;
  width: 120px;
  background-color: #FFF579;
  margin: 20px 0;
  border-radius: 21px;
}
* {
  margin:0;
  padding: 0;
  background:  #645E00;
}
.container {
  display:flex;
  flex-direction:column;
  justify-content: center;
  align-items:center;
  width: 100%;
  height: 100%;
}
.bar {
  height: 20px;
  width: 60px;
  border-radius: 38px;
  background: black;
  background-color: #FFF579;
}
</style>
