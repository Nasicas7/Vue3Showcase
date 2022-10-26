<script setup lang="ts">

import HomeViewVue from './views/HomeView.vue';


let string= "Rob";

</script>

<template>

bonjour
{{string}}  

<div class="container"></div>
<form action="">
  <input type="text" placeholder="search" name="inputext" id="">
  <button type="submit" class="button_search"></button>
</form>

</template>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container{
  width: 100%;
  min-height: 100hp;
  padding: 5%;
}

.button_search{
  width: 10hp;
  height: 10 hp;
  padding: 5%;
}


</style>