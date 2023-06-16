<script>
import NewHeader from './components/NewHeader.vue';
import NavLink from './components/NavLink.vue'

export default {
    name: 'App',
    components:{
      NewHeader,
      NavLink
    }
}
</script>

<template>
  <div>
    <NewHeader />
  </div>
  
</template>

<style lang="scss">
@import "./styles/general.scss";
</style>
