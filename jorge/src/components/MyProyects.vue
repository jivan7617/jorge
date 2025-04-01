<template>

    <div class="Proyect_title" >
        <h1 class="dm-serif-text-regular-italic"> My proyects</h1>
    </div>

    <div class="divProyect1">
        <li><p >Proyecto bootcamp Universidad de Antioquia </p></li>
        <a href="https://github.com/jivan7617/financiera1">  Entidaed Financiera </a>
        
    </div>

</template>


<script setup>

</script>

<style scoped>

.divProyect3{
    padding: auto;
    margin-right: 1rem;
    margin-left: 1rem;
}

.divProyect1{    
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
.Proyect_title{
    border: none ;
}

li{
    list-style-type: none;
    list-style: none;
    padding-bottom: 1rem;
    padding-left: 0px;
    padding-right: 0px;
}

a{
    color: rgb(6, 65, 175);
    margin-left: 1rem;
}

.dm-serif-text-regular-italic {
    font-family: "DM Serif Text", serif;
    font-weight: 400;
    font-style: italic;
    color: gray;
}


</style>