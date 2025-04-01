<template>
    <div class="div_logo"> 

        <div class="div_2">
            <ul>
                <li><img class="imgLogo" src="../assets/Gmail sin fondo.jpg" alt="imgGmail"></li>
                <li><img class="imgLogo" src="../assets/logoGitHub.png" alt="gitHub"></li>
                <li><img class="imgLogo" src="../assets/in.jpg" alt="imgGmail"></li>
            </ul>
        </div>  

        <div class="div_2">
            <ul>
                <li class="list_2"><a href="mailto:jivan7617@gmail.com">jivan7617@gmail.com</a></li>
                <li class="list_2"><a href="https://github.com/jivan7617/financiera1"> GitHub </a> <a href="https://jivan7617.github.io/jorge/"> GitPages </a></li>
                <li class="list_2"><a href="https://www.linkedin.com/in/jorge-iván-espinosa-350089195/?locale=en_US&trk=eml-email_job_alert_confirmation_01-header-25-profile">Linkedin</a></li>
            </ul>
        </div>

        

    </div>

</template>


<script setup>

</script>

<style scoped>
.div_logo{    
    width: 95%;
    padding: 0px;
    margin: 0px;
    border-radius: 15px;
    background-color: transparent;
    display: inline-flex ; 
    justify-content: center;  
    align-items: center;   
}

.div_2{
    width: 100%;
    padding: 0%;
    margin: 0px;
    border-radius: 0px;
    display: flex;
    align-items: center;
}

.imgLogo{
    width: 50px;
    border-radius: 25px;
    
}

li{
    list-style-type: none;
    list-style: none;
    padding-bottom: 1rem;
    padding-left: 0px;
    padding-right: 0px;

}
.list_2{   
    margin-bottom: 0px; 
    margin-top: 9PX;

}

a{
    color: rgb(6, 65, 175);
    padding-left: 10px;
}

   

</style>