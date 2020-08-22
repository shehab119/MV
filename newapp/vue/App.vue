<template>
  <div>
    <h2 class="center">Welcome To Meteor.js and Vue.js</h2>
    <Home />
  </div>
</template>


<script>
import Home from '../vue/components/Home.vue'

export default {
  name: "App",
  components:{
    Home,
  }

};
</script>


<style scoped>
.center {
  text-align: center;
}
</style>