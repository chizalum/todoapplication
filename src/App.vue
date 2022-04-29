<template>
  <todoapplication></todoapplication>
  <Home></Home>
</template>

<script>
import todoapplication from './components/todoapplication.vue';
import Home from './components/Home.vue';

export default {
  name: 'App',
  components: {
    todoapplication,
    Home
  }
}
</script>
