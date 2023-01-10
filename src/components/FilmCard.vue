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
    </div>
</template>
<style lang="scss">
    .card-element{
        width: calc((100% / 6));
        padding: 2rem;
        
        img{
        width: 250px;
        height: 250px;
        }

        h2{
            color: white;
            margin-top: 1.2rem;
            font-size: 1.2rem;
            text-transform: uppercase
        }
    }
</style>