<template>
  <div id="app">
   
    
    <div class="bg-transparent w-auto">
      <div class="flex">
<div class="fixed">  <sidebar-app /></div>
    
<section class="flex ml-80 w-full overflow-auto"> 
      <div class="main flex-grow">
        <main-app />
      </div>
      <div class="right ">
        <rightside-app />
      </div>
    </section>

     
     
    </div>
   
    </div>
  </div>
</template>

<script>
import SidebarComponent from './components/Sidebar.vue';
import Main from './components/Main.vue';
import RightSide from './components/RightSide.vue';
export default {
  name: 'App',
  components: {
 
    'sidebar-app':SidebarComponent,
    'main-app':Main,
    'rightside-app':RightSide,

  }
};
</script>

<style>
.bg-transparent{
  background-color: rgb(6, 3, 41);
}

.flex{
  margin-right: 5%;
}
#app {
  font-family: 'Arial', sans-serif;
}

.container {
  display: flex;
  min-height: 100vh;
}

main {
  flex: 1;
  padding: 20px;
}
</style>
