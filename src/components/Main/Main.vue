<template>
  <main class="main">
   <Header />
   <ProductInformation />
  </main>
</template>

<script>
import Header from '../Header/Header'
import ProductInformation from '../ProductInformation/ProductInformation'
export default {
  name: 'App',
  components: {
    Header,
    ProductInformation
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>