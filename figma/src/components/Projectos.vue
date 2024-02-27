<script setup lang="ts">
 
</script>

<template>

    <section>
        <h1>Projects</h1>
         <div class="colunas">

             <div class="card-project">
                 <div class="cards">
                     <h1>TITLE PROJECT</h1>
                     <div class="linguagens">
                         <span>PostgreSQL</span>
                         <span>sql</span>
                         <span>python</span>
                        </div>
                        <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint.
                            Velit officia consequat
                            duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.</p>
                        </div>
                    </div>


                    <div class="card-project">
                 <div class="cards">
                     <h1>TITLE PROJECT</h1>
                     <div class="linguagens">
                         <span>PostgreSQL</span>
                         <span>sql</span>
                         <span>python</span>
                        </div>
                        <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint.
                            Velit officia consequat
                            duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.</p>
                        </div>
                    </div>

                    <div class="card-project">
                 <div class="cards">
                     <h1>TITLE PROJECT</h1>
                     <div class="linguagens">
                         <span>PostgreSQL</span>
                         <span>sql</span>
                         <span>python</span>
                        </div>
                        <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint.
                            Velit officia consequat
                            duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.</p>
                        </div>
                    </div>

                    <div class="card-project">
                 <div class="cards">
                     <h1>TITLE PROJECT</h1>
                     <div class="linguagens">
                         <span>PostgreSQL</span>
                         <span>sql</span>
                         <span>python</span>
                        </div>
                        <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint.
                            Velit officia consequat
                            duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.</p>
                        </div>
                    </div>
                </div>
                <div class="flex-button">

                    <button>VER TODOS PROJETOS</button>
                </div>
                </section>
            </template>

<style scoped>

 
.card-project:hover{
    
    scale: 1.1;
    transition: all 0.9s ease;

}
.colunas{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 40px;
}
.card-project{
    background-color: #F0F0F0;
    width: 400px;
    padding: 10px;
}

.linguagens{
    
    display: flex; 
    gap: 20px;
}
.linguagens span{
    background-color: #8455FF;
    text-transform: uppercase;
    padding: 2px;
    border-radius: 4px;
}
.cards{
    display: flex;
    flex-direction: column;
   
}
.card-project p{
    color: #1F2626;
}
.flex-button{
    display: flex;
    justify-content: center;
    padding-top: 40px;
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
     text-transform: uppercase;
     cursor: pointer;
}
button:hover{
    background-image: linear-gradient(#582ace , #df5684);
    color: #fff;
}

@media screen and (min-width: 340px){
  .card-project{
    display: flex;
    
    justify-content: center;
    padding: 20px;
}
}

</style>