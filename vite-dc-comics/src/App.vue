<script>
  import Villain from "./components/Villain.vue";
  import Heroes from "./components/Heroes.vue"

  export default {
   // name: App è una convenzione 
   name: "App",
   //registrazione dei componenti
   components:{
    supereroi,
    supercattivi
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
  
</template>


<style>

</style>
