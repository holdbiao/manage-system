<template>
  <div class="hello">
    <!-- <h1>{{ msg }}</h1> -->
    <v-header></v-header>
  </div>
</template>

<script>
import vHeader from './header'
export default {
  name: 'home',
  data () {
    return {
      msg: 'Welcome to Your home！'
    }
  },
  components: {
    vHeader
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
