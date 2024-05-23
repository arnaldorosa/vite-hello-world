<script>
  import HelloWorld from './components/HelloWorld.vue';
  export default {
    components: {
      HelloWorld 
    },
    data() {
      return {
        message: "hello vite!"
      }
    },
    methods: {

    },
    mounted() {
      console.log("msg di saluto")
    }
  }
</script>

<template>
  <h1>Hello Vite!</h1>
</template>

<style>
</style>