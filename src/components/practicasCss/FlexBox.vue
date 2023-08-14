<template>
    <div class="caja-flex-box">
        <h1 class="titulo">Aprendiendo FlexBox</h1>
   
        <div class="contenedor"> 
            <div class="item">
                <p>A</p>    
            </div>

            <div class="item">
                <p>B</p>    
            </div>

            <div class="item">
                <p>C</p>    
            </div>
        </div>      
    </div>
</template>

<script>
    export default {
        name:'FlexBox'
    }
</script>

<style lang="css" scoped>
.caja-flex-box{
    padding-bottom: 20cm;

}
.titulo {
    font-size: 24px;
    color:hotpink;
}
.item{
    border: 1px solid ;
    padding: 1em;
    background: turquoise;
    color: whitesmoke;
  
}
.contenedor{
    border: 1px solid;
    display: flex;
    flex-direction: row;
    width: 100%;
    justify-content: space-around;
}
</style>