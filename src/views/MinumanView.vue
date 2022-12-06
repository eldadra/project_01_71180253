<template>
    <div class="gallery">
        <a href="../img/mochaccionfloat.jpg">
          <img src="../img/mochaccionfloat.jpg" alt="" width="100" height="100">
        </a>
        <span>Mochaccino Float</span>
    </div>
    <div class="gallery">
        <a href="../img/coffefloat.png">
          <img src="../img/coffefloat.png" alt="" width="100" height="100">
        </a>
        <span>Mochaccino Float</span>
    </div>
</template>

<script>
export default {
    name: 'MinumanView'
}
</script>

<style>
div.gallery {
    display: inline-block;
    margin: auto;
    border: 1px solid #ccc;
    width: 180px;
    margin: 10px;
  }
  
  div.gallery:hover {
    border: 1px solid #777;
  }
  
  div.gallery img {
    width: 100%;
    height: auto;
  }
  
  div.desc {
    padding: 15px;
    text-align: center;
  }
</style>