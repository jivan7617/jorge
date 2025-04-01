<template>
    <div class="div_1">
        <img class="photo_1" src="../assets/jorge without background.png" alt="jorge">
            <h1 class="Tangerine">Full stack software developer</h1>
        <div>
            <LogoMail></LogoMail>
        </div>
    </div>

    <div class="div_1">
        <LogoLanguage></LogoLanguage>
        <div>
          <PlayerAvatar></PlayerAvatar>  
        </div>
    </div>

    <div class="div_1">
        <EducationCard></EducationCard>
    </div>

    <div>
        <MyProyects></MyProyects>
    </div>

        
</template>


<script setup>
import LogoMail from './LogoMail.vue';
import EducationCard from './EducationCard.vue';
import LogoLanguage from './LogoLanguage.vue';
import PlayerAvatar from './PlayerAvatar.vue';
import MyProyects from './MyProyects.vue';

</script>

<style scoped>


.div_1{    
    width: 95%;
    padding: 5px;
    margin: 5px;
    border: 1px solid white ;
    border-radius: 15px;
    background-color: transparent;
    display: inline-flex ; 
    justify-content: center;  
    align-items: center;   
}

.Tangerine{
    font-family: 'Tangerine', serif;
    font-size: 40px;
    text-shadow: 8px 8px 8px #aaa;
    margin: 2%;
}

.photo_1{
  width: 180px;
  height: 180px;
  border-radius: 50px;
}
.photo_1:hover{
  width: 200px;
  height: 200px;
  border-radius: 0px;
}


</style>