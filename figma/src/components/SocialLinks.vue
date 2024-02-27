<script setup lang="ts">

</script>

<template>
     <div class="area-links">
        <h1>Redes sociais</h1>

        <div class="links">
            <a href="#" ><img src="../assets/github.png" class="img-width" ></a>
            <a href="#"><img src="../assets/gmail.png"  ></a>
            <a href="#"><img src="../assets/linkedin.png"></a>  
        </div>
     </div>
</template>
 
<style scoped>
.area-links{
    padding: 10px;
}
.links a img{
    width: 100px;
}

.links a img:hover{
   scale: 1.2;
   transition: all 0.4s ease;

   
}
h1{
    line-height: 40px;
    font-weight: 500;
    font-size: 36px;
    line-height: 40px;
    letter-spacing: 4%;
 
}
.links{
    display: flex;
    gap: 5px;
    padding: 10px;
}
.links img{
    width: 170px;
}

@media screen and (min-width: 340px){
  .links{
    display: flex;
    justify-content: center;
  }
}

</style>