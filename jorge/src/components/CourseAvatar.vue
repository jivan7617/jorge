<template>
    
        
    <div class="div_avataraCourse_1">
        <div class="div_avatarCourse_3
        ">
            
            <div class="div_avataraCourse_1">
                    <video controls class="avatarJorge" id="videoCourse">
                        <source src="../assets/avatarVideoCurso.mp4" type="video/mp4"/>
                    </video>
                    <p class="noto-serif-regular-italic">I took these courses in a virtual and self-taught way.</p>
                    <p class="noto-serif-regular-italic">Using platforms such as Platzi, Udemi and YouTube among others.</p>
                    
            </div>
            
        </div>   

            <ul class="logoMail">
                    <li><img class="imgLogo" src="../assets/Gmail sin fondo.jpg" alt="imgGmail"> <a href="mailto:jivan7617@gmail.com">jivan7617@gmail.com</a></li>
                    <li><img class="imgLogo" src="../assets/logoGitHub.png" alt="gitHub"><a href="https://github.com/jivan7617/jivan7617.github.io/settings">Github pages</a></li>
                    <li><img class="imgLogo" src="../assets/in.jpg" alt="imgGmail"><a href="https://www.linkedin.com/in/jorge-iván-espinosa-350089195/?locale=en_US&trk=eml-email_job_alert_confirmation_01-header-25-profile">Linkedin</a></li>
            </ul>
    </div>
    
</template>


<script setup>

</script>

<style scoped>
li{
    list-style-type: none;
    list-style: none;
    padding-right: 5%;
    height: 50px;
    padding-top: 10px; 
    }  

    .avatarJorge{
        width: 400px;
        height: 320px;
        border-radius: 5%;
    }

    .div_avatarCourse_3
    {
        width: 100%;
        padding: 0%;
        margin: 0px;
        border-radius: 0px;
        display: flex;
        justify-content: space-around;
  
    }

    .div_avataraCourse_1{    
        width: auto;
        padding: 1%;
        margin: 2%;
        border-radius: 15px;   
        flex-direction: column; 
        border: 1px solid red;
        justify-content: space-around;

    }   
    .logoMail{
        display: flex;
    }
    .noto-serif-regular-italic{
    font-family: "Noto Serif", serif;
    font-optical-sizing: auto;
    font-weight: 400;
    font-style: normal;
    font-variation-settings:
      "wdth" 100;
      font-size: 1.2rem;
  }

</style>