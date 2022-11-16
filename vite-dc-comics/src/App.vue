<script>
  import Villain from "./components/Villain.vue";
  import Heroes from "./components/Heroes.vue";

  export default {
   // name: App è una convenzione 
   name: "App",
   //registrazione dei componenti
   components: {
    Supereroi,
    Supercattivi
   },
   data(){
    return {
      Eroe1: "Superman",
      Eroe2: "Batman",
      Eroe3: "Wonder Woman",

      Cattivo1: "Doomsday",
      Cattivo2: "Joker",
      Cattivo3: "Morbius"

    }
   }
  }
</script>

<template>
  <Supereroi :Eroe1="Eroe1" :Eroe2="Eroe2" :Eroe3="Eroe3"/>
  
  <Supercattivi :Cattivo1="Cattivo1" :Cattivo2="Cattivo2" :Cattivo3="Cattivo3"/>
</template>


<style>

</style>
