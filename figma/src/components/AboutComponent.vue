<script setup lang="ts">

</script>

<template>
    <aside>
        <h1>About me</h1>
        <div class="about-desc">
            <img src="../assets/line.png" alt="" width="4px" height="153px"  >
            <p>The long barrow was built on land previously inhabited in the Mesolithic period.
                It consisted of a sub-rectangular earthen tumulus, estimated to have been 15 metres
                (50 feet) in length, with a chamber built from sarsen megaliths on its eastern end. 
                Both inhumed and cremated human remains were placed within this 
                chamber during the Neolithic period, representing at least nine or ten individuals.</p>
        </div>
    </aside>
</template>
 
<style scoped>

.about-desc{
    display: flex;
    gap: 20px;
    padding: 10px;
    align-items: center;
    line-height: 30px;
}

@media screen and (min-width: 340px) {
   .about-desc {
    text-align: center;
    padding: 20px;
}
div img{
        display: flex;
        justify-content: center;
        height: 400px;
    }
    h1{
        display: flex;
        justify-content: center;
    }
}
</style>