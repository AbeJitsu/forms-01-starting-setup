<template>
  <the-form></the-form>
</template>

<script>
import TheForm from './components/TheForm.vue';

export default {
  components: {
    TheForm
  }  
}
</script>

<style>
* {
  box-sizing: border-box;
}

html {
  font-family: sans-serif;
}

body {
  margin: 0;
  background-color: #292928;
}

h1 {
  margin: 0;
  padding: 1rem;
  color: #fff;
  background-color: #292928;
  text-align: center;
}
</style>