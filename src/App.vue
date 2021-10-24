<template>
<div>
  <Header/>
</div>
<div class="product_container">
  
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
    <Container />
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Container from './components/Container.vue'


export default {
  name: 'App',
  components: {
    Header,
    Container,
  },
}


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.product_container{
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  
}
</style>
