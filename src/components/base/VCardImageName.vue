<template>
    <div class="card-image-name">
        <img 
        class="card-image-name__img"
        src="../../assets/person.png"
        >
        <p class="card-image-name__name">La gata Ladrona</p>

    </div>
</template>

<script>
    export default {
        name: 'VCardImageName'
    }
</script>

<style lang="scss" scoped>

.card-image-name{

    &__img {

    width: 100px;
    height: 100px;
    border-radius: 50%;
    }
    &__name {
        font-weight: bold;
        color: white;
    }

}

</style>