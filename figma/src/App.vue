<script setup lang="ts">
import { onUnmounted, ref } from 'vue';
import FooterView from './components/FooterView.vue';
import NavbarLinks from './components/NavbarLinks.vue';
import SocialLinks from './components/SocialLinks.vue';

 
onUnmounted(()=>{
 
  
})
</script>

<template >
  <div >
 

  <header>
    <nav>
      <NavbarLinks/>
    </nav>
  </header>
  <footer>
    <RouterView />
    <SocialLinks />
    <FooterView/>
  </footer>
 
  </div>
</template>

<style scoped>
 
</style>
