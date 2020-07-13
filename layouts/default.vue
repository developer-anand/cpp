<template>
  <div>
    <Header />
    
    <Nuxt />
    
    <Footer />
  </div>
</template>

<script>
import Header from './partials/Header.vue'
import Footer from './partials/Footer.vue'
export default {
  components: {
    Header,
    Footer
  },
  head() {
    return {
      link: [
        {
          "rel": "stylesheet",
          "href": "https://fonts.googleapis.com/css2?family=Muli:wght@300&display=swap" 
        }
      ]
    }
  },
      mounted () {
      this.$nextTick(() => {
      this.$nuxt.$loading.start()

      setTimeout(() => this.$nuxt.$loading.finish(), 500)
    })
  }
 }

</script>

<style lang="scss">
html {
  font-family:
    'Lato';
  font-size: 16px;

  &, body {
    width: 100%;
    height: 100vh;
    margin: 0;
    padding: 0;
    
  }
}

.container {
  width: 80%;
  margin: 0 auto;
  height: auto;

    main {
      width: 100%;
      height: auto;
      display: flex;
      flex-direction: column;
      align-items: center;
    
    h1{
      font-size: 2em;
      word-spacing: .3em;
    }
    p{
      display: flex;
       align-items: center;
      text-indent: 3em;
      font-size: 1em;
      line-height: 1.5;
      margin: 0;
      color:black;
      display: block;
      text-align: center;
      margin-bottom: 5rem;
    padding: 1rem;
    padding-top: 1rem;
    padding-right: 1rem;
    padding-bottom: 1rem;
    padding-left: 1rem;
    
    padding: 0;
    font-family: Muli;
    font-size: 1.5rem;
    font-weight: 400;
    }
    *, :after, :before {
    box-sizing: border-box;
    margin: 0;
}
    }
}
</style>
