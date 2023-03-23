<script>
export default{
    data(){
        return{
            imgName:'04.webp'
        }
    },
    methods: {
        //creo una funzione che che indipendentemente dall'immagine sa sempre il percorso
      getImgePath:function(imgPath){
        return new URL(`../assets/img/${imgPath}`, import.meta.url).href;
      }  
    },
}
</script>

<template>
    <div>
        <img src="../assets/img/04.webp" >
        <img :src="getImgePath(imgName)" >
    </div>
</template>

<style>
</style>