<script setup lang="ts">

</script>

<template>

    <section>
        <div class="container-description">

            <div class="section-left">
                
                <h1>SOFWARE DEVELOPER</h1>
                <h2>Fernanda</h2>
                <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do 
                    amet sint. Velit officia consequat duis enim velit mollit. Exercitation 
                    veniam consequat sunt.</p>
                    <button>Download CV</button>
                </div>
                <div class="section-rigth">
                    <img src="../assets/sectionImg.svg" alt="" width="380px" height="338px"  >
                </div>
            </div>
            </section>
        </template>

<style scoped>

.container-description{
    display: flex;
    flex: 1;
    padding: 10px;
    gap: 20px;
}
 
button{
     background-image: linear-gradient(#5222D0 , #FF6196);
     padding: 5px  10px;
     border-radius: 10px;
     border: none;
     width: 180px;
     height: 45.51px;
     color: #fff;
     size: 18px;
     font-weight: 400;
     line-height: 22px;
     cursor: pointer;
}
button:hover{
    background-image: linear-gradient(#582ace , #df5684);
    color: #fff;
    margin: 20px ;
}
p{
    font-weight: 400;
    size: 24px;
    line-height: 28px;
    letter-spacing: 4%;
}

@media screen and (max-width: 412px) {
    .container-description{
    
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    
}
.section-left{
    display: flex;
    justify-content: center;
    flex-direction: column;
}
   
 .section-rigth img{
    
 
    padding: 10px;
    width: 300px;
 }
}
</style>