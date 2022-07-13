<template>
  <main class="main">
   <Header />
   this is main!!!
  </main>
</template>

<script>
import Header from '../Header/Header'

export default {
  name: 'App',
  components: {
    Header
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