<script >
  import HeaderComics from './components/HeaderComics.vue';
  import MainComics from './components/MainComics.vue';
  import FooterComics from './components/FooterComics.vue';
  
  export default {
      components:{
        HeaderComics,
        MainComics,
        FooterComics,
      }
  }
  
</script>

<template>
  <header>
    <HeaderComics />
  </header>

  <main>
    <MainComics />
  </main>

  <footer>
    <FooterComics />
  </footer>

</template>

<style>
     .container{
        width : 80%;
        height: 100%;
        margin: 0 auto;
   }
</style>
