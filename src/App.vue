<template>

  <Home />  

</template>

<script>

import Home from './components/Home.vue'

export default {
  name: "App",
  components: {
     Home
  },
  data(){
    return {
      title: "Hello World :)"
    }
  }
}
</script>
