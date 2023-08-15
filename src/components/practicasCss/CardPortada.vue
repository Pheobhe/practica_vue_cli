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
                <button class="card-portada__content__control__btn">Ver mas</button>
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

</style>