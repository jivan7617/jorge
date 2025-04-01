<template>
    <div>
        <div>   
            <h1 class="dm-serif-text-regular-italic">Other courses</h1>
        </div>

            <ul>
                <li><img class="imgLogo" src="../assets/logoPython.jpg"  alt="logoPython"  @mouseenter="PlayAudioPython()" @mouseout="StopAudioPython()"></li>
                <li><img class="imgLogo" src="../assets/logo fastApi.png" alt="logo fastApi" @mouseenter="PlayAudioFastApi()" @mouseout="StopAudioFastApi()"></li>
                <li><img class="imgLogo" src="../assets/logoJava.png" @mouseenter="PlayAudioJava()" @mouseout="StopAudioJava()"></li> 
                <li><img class="imgLogo" src="../assets/javascript.png" @mouseenter="PlayAudioJavaScript()" @mouseout="StopAudioJavaScript()"></li>
                <li><img class="imgLogo" src="../assets/logoCSS.png"  @mouseenter="PlayAudioCSS()" @mouseout="StopAudioCSS()"></li>
                <li><img class="imgLogo" src="../assets/logoVue.png" @mouseenter="PlayAudioVue()" @mouseout="StopAudioVue()"></li>
                <li><img class="imgLogo" src="../assets/logoSQL.png"  @mouseenter="PlayAudioSQL()" @mouseout="StopAudioSQL()"></li>
                <li><img class="imgLogo" src="../assets/logoMySQL.png" @mouseenter="PlayAudioMySQL()" @mouseout="StopAudioMySQL()"></li>
                <li><img class="imgLogo" src="../assets/logoDocker.png" @mouseenter="PlayAudioDocker()" @mouseout="StopAudioDocker()"></li>

            </ul>

    </div>
</template>

<script setup>

let audioFastApi = new Audio(require('../assets/audios/FastApiCourse.mp3')) 
const PlayAudioFastApi = () => {
  audioFastApi.play()  
}
const StopAudioFastApi = () => {
    audioFastApi.pause()
} 

let audioPython = new Audio(require('../assets/audios/PythonCourse.mp3')) 
const PlayAudioPython = () => {
  audioPython.play()  
}
const StopAudioPython = () => {
    audioPython.pause()
} 

let audioJava = new Audio(require('../assets/audios/JavaCourse.mp3')) 
const PlayAudioJava = () => {
  audioJava.play()  
}
const StopAudioJava = () => {
    audioJava.pause()
} 

let audioJavaScript = new Audio(require('../assets/audios/JavaScriptCourse.mp3')) 
const PlayAudioJavaScript = () => {
  audioJavaScript.play()  
}
const StopAudioJavaScript = () => {
    audioJavaScript.pause()
}

let audioCSS = new Audio(require('../assets/audios/CSScourse.mp3')) 
const PlayAudioCSS = () => {
  audioCSS.play()  
}
const StopAudioCSS = () => {
    audioCSS.pause()
}

let audioVue = new Audio(require('../assets/audios/VueCourse.mp3')) 
const PlayAudioVue = () => {
  audioVue.play()  
}
const StopAudioVue = () => {
    audioVue.pause()
}

let audioSQL = new Audio(require('../assets/audios/SQLcourse.mp3')) 
const PlayAudioSQL = () => {
  audioSQL.play()  
}
const StopAudioSQL = () => {
    audioSQL.pause()
}

let audioMySQL = new Audio(require('../assets/audios/MySQLcourse.mp3')) 
const PlayAudioMySQL = () => {
  audioMySQL.play()  
}
const StopAudioMySQL = () => {
    audioMySQL.pause()
}

let audioDocker = new Audio(require('../assets/audios/DockerCourse.mp3')) 
const PlayAudioDocker = () => {
  audioDocker.play()  
}
const StopAudioDocker = () => {
    audioDocker.pause()
}


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