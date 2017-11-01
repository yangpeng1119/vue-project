<template>
  <div class="hello">
      <Index-header />
  </div>
</template>

<script>
import Header from './Header.vue'
export default {
  name: 'HelloWorld',
  data () {
    return {
    	
    }
  },
  components: {
  	'Index-header' :Header
  }
}
</script>

<style scoped>

</style>