<template>
  <div>
    <div>
      <Header/>
    </div>
    <div class="product_container">
      
    <Container  :key="product.id" v-for="product in products" :product="product" />

      </div>
      <div>
        <Footer/>
      </div>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Container from './components/Container.vue'
import Footer from './components/Footer.vue'



export default {
  name: 'App',
  components: {
    Header,
    Container,
    Footer,
  },
  data(){
    return{
      products: []
    }
  },
  created(){
    this.products = [
      {
        id: 1,
        type: 'JVC200123',
        name: 'Acme Disc',
        price: '1.00 $',
        size: 'Size: 700 MB',
      },
            {
        id: 2,
        type: 'GGWP0007',
        name: 'War and Peace',
        price: '20.00 $',
        size: 'Weight: 2 KG',
      },
            {
        id: 3,
        type: 'TR120555',
        name: 'Chair',
        price: '40.00 $',
        size: 'Dimension: 24x45x15',
      },   
    ]
  },
  methods: {

  }
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
