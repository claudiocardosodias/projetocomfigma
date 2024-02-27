<script setup lang="ts">
import { RouterView , RouterLink } from 'vue-router';

</script>

<template>
    
    <div class="footer-view">
        <p>Desenvolvido pelo figma da Fernanda Kipper</p>
    </div>

</template>

<style scoped> 
 
p{
    text-align: center;
    font-weight: 400;
    font-size: 24px;
}

@media screen and (min-width: 340px){
  p{
    display: flex;
    justify-content: center;
    font-size: 18px;
  }
}

</style>