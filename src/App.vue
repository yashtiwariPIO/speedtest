<template>
 <h1>hello world</h1>
 <Header />
 <Section />
 <Footer />
  
</template>

<script>
import Header from "./components/header"
import Section from "./components/section"
import Footer from "./components/footer"

export default {
  name: 'App',
  components: {
   Header,
   Section,
   Footer
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
</style>
