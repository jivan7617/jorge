<template>
    <div>
        <div>   
            <h1 class="dm-serif-text-regular-italic">Education</h1>
        </div>

        <div class="div_education_1">
            <div class="div_education_3">
                <div>
                    <h2 class="dm-serif-text-regular-italic">Institution</h2>
                    <p class="noto-serif-regular-italic">Univesrsity  Politécnico Gran Colombiano</p>
                    <p class="noto-serif-regular-italic">Univesrsity  of Antioquia</p>
                    <p class="noto-serif-regular-italic">SENA</p>
                </div>
            </div>
            
            <div class="div_education_3">
                <div>
                    <h2 class="dm-serif-text-regular-italic">Course program </h2>
                    <p class="noto-serif-regular-italic">Software engineering</p>
                    <p class="noto-serif-regular-italic">Bootcamp full stack programming</p>
                    <p class="noto-serif-regular-italic">English B1</p>
                </div>        
            </div>

            <div class="div_education_3">
                <div>
                    <h2 class="dm-serif-text-regular-italic">Duration</h2>
                    <p class="noto-serif-regular-italic">Sixth semester completed</p>
                    <P class="noto-serif-regular-italic">1 term</P>
                    <p class="noto-serif-regular-italic">1 year</p>   
                </div>
            </div>
        </div>

        <AudioLogo></AudioLogo>


            

    </div>
</template>


<script setup>
import AudioLogo from './AudioLogo.vue';


</script>


<style scoped>


.dm-serif-text-regular-italic {
    font-family: "DM Serif Text", serif;
    font-weight: 400;
    font-style: italic;
    color: gray;
}

.imgLogo{
        width: 50px;
        height: 50px;
        border-radius: 25px;
        margin-top: 2rem; 
        margin-bottom: 2rem;       
    }

.imgLogo:hover{
    width: 80px;
    height: 80px;
    }

li{
    list-style-type: none;
    list-style: none;
    padding-right: 4rem;
    padding-bottom: 2rem;
    height: 50px;
    padding-top: 5rem;

    display: inline;    
}  

.div_education_3{
    padding: auto;
    margin-right: 1rem;
    margin-left: 1rem;
}

.div_education_1{    
    width: 95%;
    padding: 0px;
    margin: 0px;
    border: 1px solid white ;
    border-radius: 15px;
    background-color: transparent;
    display: inline-flex ; 
    justify-content: center;  
    align-items: center;   
}

.noto-serif-regular-italic{
    font-family: "Noto Serif", serif;
    font-optical-sizing: auto;
    font-weight: 400;
    font-style: normal;
    font-variation-settings:
      "wdth" 100;
      font-size: 1rem;
  }

  .post-btn{
    padding: 15px;
    background-color: rgb(150, 241, 241);
    color: grey;
    border-radius: 5px;
    border: 0;
    outline: 0;
}

</style>