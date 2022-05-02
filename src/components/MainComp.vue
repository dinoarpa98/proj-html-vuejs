<template>
<main>
    <FoodDescr/>
    <JumboBan/>
</main>
</template>

<script>
import "bootstrap"
import FoodDescr from './MainComps/FoodDescr.vue'
import JumboBan from './MainComps/JumboBan.vue'

export default {
  name: 'MainComp',
  components:{
      FoodDescr,
      JumboBan
  }
}
</script>

<style scoped lang="scss">

</style>
```