<script>
    import MainJumbotron from './MainJumbotron.vue';
    export default {
            components:{
                MainJumbotron
            }
    }
</script>
<template>
    <MainJumbotron />
    <div class="wrapper-top">
        <div class="container">
            <h1> --> Content goes here </h1>
        </div>
    </div>
    <div class="wrapper-bottom">

    </div>
</template>


<style scoped>
    .wrapper-top{
        width: 100%;
        height: 110px;
        background-color: #1c1c1c;
    }

    .wrapper-top h1{
        color: white;
    }

    .wrapper-bottom{
        width: 100%;
        height: 130px;
        background-color: #0282f9;
        
    }
</style>