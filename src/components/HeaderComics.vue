<template>
    <div class="wrapper">
        <div class="container">
            <div class="img-wrapper">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <nav>
                <ul>
                    <li v-for="items in navItems">{{ items.text }}</li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            navItems : [
                {
                  text : 'Characters',
                  active :  false
                },
                {
                  text : 'Comics',
                  active :  true  
                },
                {
                  text : 'Movies',
                  active :  false  
                },
                {
                  text : 'Tv',
                  active :  false  
                },
                {
                  text : 'Games',
                  active :  false  
                },
                {
                  text : 'Collectibles',
                  active :  false  
                },
                {
                  text : 'Videos',
                  active :  false  
                },
                {
                  text : 'Fans',
                  active :  false  
                },
                {
                  text : 'News',
                  active :  false  
                },
                {
                  text : 'Shop',
                  active :  false  
                },
            ]
        }
    },
}
</script>

<style>
    .wrapper {
        width : 100%;
        height : 100px;
    }

   .container{
        width : 80%;
        display: flex;
        margin: 0 auto;
        justify-content: space-between;
   }

   nav ul{
    display: flex;
    list-style-type: none;
   }
</style>