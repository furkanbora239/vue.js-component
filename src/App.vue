<template>
  <div class="container">
    <bas></bas>
    <hr>
    <list></list>
    <hr>
    <foot></foot>
  </div>
</template>

<script>
import baslik from './baslik.vue'
import list from './list.vue'
import foot from './foot.vue'
export default {
  components:{
    "bas": baslik,
    "list": list,
    "foot": foot
  }
  
}
</script>

<style>
body{
  background: rgba(117, 116, 55, 0.404);
}
</style>
