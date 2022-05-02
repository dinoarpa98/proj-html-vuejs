<template>
  <div id="app">
       <HeaderComp/>
       <MainComp/>
  </div>
</template>

<script>
import "bootstrap"
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

*{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

.bg-header{
    background-image: url('./assets/img/slider52x.jpg');
    background-size: cover;
    height: 1200px;
    
}
</style>
