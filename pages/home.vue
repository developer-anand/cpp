<template>
  <div class="container">
   
    <main>
      <h1>Welcome to NOVEL</h1>
        <v-carousel hide-delimiters>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
  </v-carousel><br><br>
  <p style="background-color:Tomato;"><strong> Since 2005 Control Electrical Engineers have been working on a program of investment in staff, working on a long term strategy to recruit and retain good quality staff. Control Electrical Engineers believes in recruiting team members who are qualified and efficient in carrying out our installations. This has ensured that we are capable of taking projects upto £2 million per annum and single projects in access of a million Sterling pound at a time.

Control Electrical Engineers pride themselves in high quality workmanship attained through their wide expertise with attention to detail and personal service. We offer a design and build package from feasibility study through to complete installation and end user maintenance.

Our success is built on our total commitment to quality and meeting client’s requirements by coupling innovation and technology. Each project is undertaken in a manner to provide the management, construction and finishing skills that will produce the highest quality of work in the most economical manner, all within the shortest and most cost effective time scale.

Control Electrical Engineers are registered with the Construction Industry Scheme (CIS) with HM Revenue & Customs and are holders of a CIS 6 certificate.</strong></p>
<h3 class="review">
Mission & Vision
SIMPLE
BRING QUALITY
INTEGRITY
Customer Reviews


Lorem ipsum

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit.

</h3>
      </main>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
//import logo from './components/Logo.vue'
export default Vue.extend({
  
   data () {
      return {
        items: [
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
        ],
      }
    }
})
</script>

<style>
.home{
  image-resolution: auto;
}
.review{
  text-align: center;
}
</style>