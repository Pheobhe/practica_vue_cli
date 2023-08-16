<template>
    <div class="card-portada">
        <img 
        class="card-portada__img"
        src="../../assets/fondo.png"
        >
        <div class="card-portada__content">
            <img 
            class="card-portada__content__img"
            src="../../assets/person.png"
            >
            <p class="card-portada__content__name">La gata Ladrona</p>

            <div class="card-portada__content__reporter">
                <div class="card-portada__content__reporter__items">
                    <p class="card-portada__content__reporter__items__number">20</p>
                    <p class="card-portada__content__reporter__items__text">Articulos</p>
                </div>
                <div class="card-portada__content__reporter__items">
                    <p class="card-portada__content__reporter__items__number">5</p>
                    <p class="card-portada__content__reporter__items__text">Proyectos</p>
                </div>
                <div class="card-portada__content__reporter__items">
                    <p class="card-portada__content__reporter__items__number">1.5</p>
                    <p class="card-portada__content__reporter__items__text">Años de Experiencia</p>
                </div>
            </div>
            <div class="card-portada__content__control">
                <button class="card-portada__content__control__btn">Conectar</button>
                <button class="card-portada__content__control__btn celeste">Ver mas</button>
            </div>


        </div>


    </div>
</template>

<script>
    export default {
        name: 'CardPortada'
    }
</script>

<style lang="scss" scoped>

.card-portada{
        border: 2px solid;
        width: 1000px;
        height: 400px;
        position: relative;
        display: flex;
        justify-content: center;


        &__img{
            width: 100%;
            height: 100%;
           
        }
        &__content{
            position: absolute;
            top: 0px;
            left: 0px;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;

            &__img{
               width: 80px;
               height: 80px;
               border-radius: 50%;
            }
            &__name{
                color: white;
                font-weight: bold;
                margin-bottom: 5px;
                    
                }
        
                &__reporter{
                    border-top: 1px solid white;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    text-align: center;
                    

                    &__items{
                        width: 100px;
                        color: white;
                        &__number{
                            font-weight: bold;
                            }
                        &__text{
                            font-size: 12px;
                            }
                        }
                }
            &__control{

                &__btn{
                    background: rgb(53, 207, 53);
                    padding: 5px 2em 5px 2em;
                    margin: 5px;
                    border: none;
                    border-radius: 10px;
                    color: white;
                    &.celeste{
                        background:  #3498db;
                    }

                }
            }
        }
}

</style>