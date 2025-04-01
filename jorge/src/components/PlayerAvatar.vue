<template>
    <div class="div_avatar">
        
        <div class="div_avatar_2">
            <video controls class="avatarJorge">
                <source src="../assets/avatarJorgeEnglish.mp4" type="video/mp4"/>
            </video>
        </div>

        <div class="div_avatar_2">
            <video controls class="avatarJorge">
                <source src="@/assets/avatarJorgeSpanish.mp4" type="video/mp4"/>
            </video>
        </div>

    </div>
      
</template>

<script setup>


</script>


<style scoped>
.avatarJorge{
    width: 300px;
    height: 260px;
    border-radius: 5%;
    }

.div_avatar{    
    width: 100%;
    padding: 0px;
    margin: 1px;
    border-radius: 15px;      
 }

 .div_avatar_2{
    width: 100%;
    padding: 0%;
    margin: 1rem;
    border-radius: 0px;
    display: flex;
    justify-content: space-around;
    }

</style>