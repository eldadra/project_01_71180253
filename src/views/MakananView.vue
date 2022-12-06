<template>
    <div class="gallery" @click="move('gigamac')">
        <a href="../img/burger.jpg">
          <img src="../img/burger.jpg" alt="" width="100" height="100">
        </a>
        <span>GigaMac</span>
    </div>
    <div class="gallery"  @click="move('bigmac')">
        <a href="../img/burger2.jpg">
          <img src="../img/burger2.jpg" alt="" width="100" height="100">
        </a>
        <span>BigMac</span>
    </div>
</template>

<script>
export default {
    name: 'MakananView',
    methods: {
        move() {
            
        }
    }
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