<template>
  <div class="container">
   
    <main>
      <img class="sam" src="~/assets/sam.png">
         <br><br>
      <h1>Main Services</h1>
      <br>
      <br>
      <p>
        
              Providing electrical services for over 30 years, which has
              allowed us to diversify, and offer our customers a one stop shop
              for all electrical, ancillary services, air-conditioning and
              ventilation on a design and build basis.
            
      </p>
      <br>
      <p>
        
              All work is carried out to BS 7671, and we comply with all IEEE
              17th Edition writing regulations, keeping us one step ahead of
              our competitors.
      </p>
      <div class="service">
      
             <img src="~/assets/service.png" 
             alt="Anand Jha" 
              />
              <br>
              <br>
               <img src="~/assets/work.png" 
             alt="Anand Jha" 
              />
              <br>
              <br>
              <br>
               <img src="~/assets/vision.png" 
             alt="Anand Jha" 
              />
              </div>
    
    </main>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  components: {

  },
  head() {
    return{
      title: "cee"
    }
  }
})
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
*, :after, :before {
    box-sizing: border-box;
    margin: 0;
}
.sam{
 
  height: 70vh;
  margin-top: 0;

}
h1 {
  font-size: 1.7rem;
    margin-bottom: 1.5rem;
    text-align: center;
    font-weight: 700;
    letter-spacing: 2px;
    font-family: Spartan;
}
</style>