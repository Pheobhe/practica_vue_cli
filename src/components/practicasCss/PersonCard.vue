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
            <button class="card-person__control__btn celeste">Invitar</button>
            <button class="card-person__control__btn">Pasar</button>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'PersonCard'
    }
</script>


<style lang="scss" scoped>
    .card-person{
        border: 1px solid;
        width: 400px;
        padding: 2em;
        border-radius: 10px;
        margin: 2em;
        border-color: #95a5a6;
        display: flex;
        flex-direction: column;
        justify-content:  center;
        align-items: center;
        
        &__img {
            width:  100px;
            height: 100px;
            border-radius: 50%;
        }
        &__name{
            font-size: 18px;
            font-weight: bold;
            margin-bottom: px;
            color: #000;  
        }
        &__seudonimo{
            display:block;
            font-size: 12px;
            color: #7f8c8d;
            margin-bottom: 1em ;
        }
        &__control{
            display: flex;
            width: 100% ;
            justify-content: space-around;
            align-items: center;

            &__btn{
                padding: 5px 30px 5px 30px;
                background-color: #27ae60;
                border:none;
                color: white;
                border-radius:10px;
                font-size: 16px;
                &.celeste{
                    background-color: #2980b9;
                }
            }
        }
        
    }


</style>