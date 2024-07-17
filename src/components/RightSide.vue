<template>

<div class=" h-12 right">
    <!--right menu-->

    <search-app/>
    <trends-app/>

    <follow-app/>

    <footer-app/>


        <!--second-trending tweet section-->



    <!--third-people suggetion to follow section-->




</div> 


    </template>

    <script>

    import Search from './Search.vue'
    import Trends from './Trends.vue'
     import Footer from './Footer.vue'
    import Follow from './Follow.vue'
    export default {
      name: 'mon-composant',
      components:{
    'search-app':Search,
    'trends-app':Trends,
    'footer-app':Footer,
    'follow-app':Follow
  }
    };
    </script>

    <style scoped>

    </style>
