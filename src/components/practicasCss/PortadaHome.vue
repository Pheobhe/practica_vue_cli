<template>
   
    <div class="card-portada">
        <img 
        class="card-portada__img"
        src="../../assets/fondo.png"
        >
        <div class="card-portada__content">
          
            <v-card-image-name/>    

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
                <v-button-primary 
                titulo="Conectar"
                />
                <v-button-primary 
                titulo="Ver mas" 
                main-color=" #3498db"
                />
              
            </div>


        </div>


    </div>
</template>

<script>

    import VCardImageName from '@/components/base/VCardImageName'
    import VButtonPrimary from '@/components/base/VButtonPrimary'

    export default {
        name: 'PortadaHome',

        components: {
            VCardImageName,
            VButtonPrimary
        }
    }
</script>

<style lang="scss" scoped>

@import "../../_variables.scss";
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
                color: color2;
                font-weight: bold;
                margin-bottom: 5px;
                    
                }
        
                &__reporter{
                    border-top: 1px solid $color2;
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
         
        }
}

</style>