<template>
  <hello-world />
</template>

<script>
import HelloWorld from '../components/HelloWorld'

export default {
  name: 'Home-page',

  components: {
    HelloWorld
  },

  mounted () {
    console.log('>>>', process.env.VUE_APP_GOOGLE_CLIENT_ID)
  }
}
</script>
