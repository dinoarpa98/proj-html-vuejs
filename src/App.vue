<template>
  <div id="app">
       <HeaderComp/>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp
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
