<template>
  <the-navbar></the-navbar>
  <router-view />
</template>

<script lang="ts">
  import TheNavbar from "../src/components/UI/TheNavbar.vue";
import { defineComponent } from "vue";
export default  defineComponent({
  components:{ TheNavbar}
});
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Ribeye+Marrow&display=swap');
  *{
    box-sizing: border-box;
    font-family: 'Ribeye Marrow', cursive;
    
  }
  html,body{
    margin: 0;
  }
</style>