<template>
  <div id="app">
    <Navbar />
    <router-view/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
console.log(process.env.VUE_APP_APIKEY);
export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>

</style>
