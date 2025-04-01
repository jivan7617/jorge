<template>
   <PresentationCard></PresentationCard>
</template>

<script>
import PresentationCard from './components/PresentationCard.vue';

export default {
  name: 'App',
  components: {
    PresentationCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body{
  background: powderblue;
 
}
</style>
