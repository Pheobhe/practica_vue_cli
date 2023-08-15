<template>
    <div class="card-simple">

        <img 
            class="card-simple__img"
            src="../../assets/cara.png"
        >
        <p class="card-simple__titulo">Titulo de la Tarjeta</p>
        <p class="card-simple__subtitulo">Subtitulo de la Tarjeta</p>
        <p class="card-simple__text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam libero voluptatem voluptate aspernatur corporis inventore sequi ipsam cumque distinctio quod eligendi ratione magnam ipsum a eveniet nemo, recusandae suscipit incidunt.</p>
        
        <button class="card-simple__btn">Visitar</button>

    </div>
</template>

<script>
    export default {
         
        name: 'CardSimple'
    }
</script>

<style lang="css" scoped>

.card-simple{
    border: 1px solid;
    width: 400px;
    text-align: center;
    padding-bottom: 1em;
}
.card-simple__img{
    width: 100%;
}
.card-simple__titulo{
    font-size: 18px;
    font-weight: bold ;
    color:#2c3e50;
}
.card-simple__subtitulo{
    color: #e74c3c;
    font-size: 14px;
}
.card-simple__text{
    font-size: 16px;
    color: #95a5a6;
    margin-left: 10px;
    margin-right: 10px;
}
.card-simple__btn{
    padding: 5px 2em 5px 2em;
    background-color:  #27ae60;
    border:none;
    color: white;
    font-size: 18px;
    border-radius: 10px;

}

</style>