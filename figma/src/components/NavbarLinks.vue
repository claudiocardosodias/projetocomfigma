<script setup lang="ts">
import { RouterView , RouterLink } from 'vue-router';

</script>

<template>

    <nav>
        <div class="links">
            
            <router-link to="/">Home</router-link>
            <div class="links-rigth">

                <router-link to="/project">Project</router-link>
                <router-link to="/contact">Contact</router-link>
            </div>
        
        </div>
  
    </nav>

</template>

<style scoped>

nav{
    position: sticky;
}
.links{
    display: flex;
    justify-content: space-between;
    padding: 30px 30px;
    text-decoration: none;
    color: #0000;
   a{

       text-decoration: none;
       color: #3f4d4d;
   } 
   a:hover{
    color: #0b0e0e;
    
   }
    
}
.links-rigth{
    display: flex;
    gap: 20px;
}

@media screen and (max-width: 340px) {
    .links{
        display: flex;
    justify-content: space-around;
    }
}
 
</style>