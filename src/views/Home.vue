<template>
  <div class="home">
    <Calculator />
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Calculator from '@/components/Calculator.vue';

export default {
  name: 'Home',
  components: {
    Calculator,
  },
};
</script>
