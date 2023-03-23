

<script>
//importo il componente esterno tramite il percorso 
  import AppTitle from './components/AppTitle.vue';
  import AppHero from './components/AppHero.vue';
  //esporto in tutta l'app
  export default{
    //dichiaro il componente da utilizare in template
    components:{
      AppTitle,
      AppHero
    }
  }
</script>

<template>
  <AppTitle/>
</template>

<style scoped>

</style>
