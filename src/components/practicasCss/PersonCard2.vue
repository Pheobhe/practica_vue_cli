<template>
    <div class="card-person">
        <img 
        class="card-person__img" 
        src="../../assets/person.png" 
         >

        <p class="card-person__name">Namy One Piece</p>
        <span class="card-person__seudonimo">
            La gata ladrona
        </span>
        
        <div class="card-person__control">
            <button class="card-person__control__btn color-celeste">Invitar</button>
            <button class="card-person__control__btn">Pasar</button>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'PersonCard'
    }
</script>


<style lang="css" scoped>
.card-person{
    border: 1px solid ;
    width: 400px;
    padding: 2em;
    text-align: center;
    border-radius: 10px;
    margin: 2em;
    border-color: #7f8c8d;
}
.card-person__img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
}

.card-person__name{
    font-size: 18px;
    font-weight: bold;
    margin-bottom: px;
    color: #000;
}
.card-person__seudonimo{
    display:block;
    font-size: 12px;
    color: #7f8c8d;
    margin-bottom: 1em ;
}
.card-person__control{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.card-person__control__btn{
    padding: 5px 30px 5px 30px;
    background-color: #27ae60;
    border:none;
    color: white;
    border-radius:10px;
    font-size: 16px;
}
.color-celeste{
    background-color: #2980b9;
}

</style>