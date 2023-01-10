<script>
    export default {
        name: 'FilmCard',
        props:[
            'imageUrl',
            'filmPrice',
            'filmName',
            'filmType'
        ]
    }
</script>

<template>
    <div class="card-element">
       <img :src="imageUrl" :alt="filmName">
       <h2>{{ filmName }}</h2>
       <p>{{ filmPrice }}</p>
    </div>
</template>

<style lang="scss">
    .card-element{
        width: calc(100% / 6);
        max-height: 250px;
        padding: 0 .5rem ;
        margin-bottom: 7rem;
        
        img{
            object-fit: cover ;
            object-position: top;
            width: 100%;
            height: 100%;
        }

        h2{
            color: white;
            margin-top: 1.2rem;
            font-size: 1.1rem;
            text-transform: uppercase
        }
    }
</style>