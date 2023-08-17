<template>
     <button class="btn-primary " :style="{background: mainColor}">{{titulo}}</button>
   
</template>

<script>
    export default {
        name: 'VButtonPrimary',
        props: {
            titulo: String,
            mainColor: String
        }
    }
</script>

<style lang="scss" scoped>

    .btn-primary{
        background: rgb(53, 207, 53);
        padding: 5px 2em 5px 2em;
        margin: 5px;
        border: none;
        border-radius: 10px;
        color: white;
      
       }

</style>