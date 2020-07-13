<template>
 <div class="page-content">
  
 <footer>
   <div class="footer-container">
     <div class="left-c">
       <img src="~/assets/footerslogo.png" alt="" class="logo">
       <p>Based in the North West London, Control Electrical Engineers Ltd have been trading since 1991,
          providing professional services to domestic social commercial and industrial customers in both 
          the private and public sectors, across England (U.K.)
          
      </p>  
     
     <p class="right-text">
      <br>
          © 2019 CEE. All rights reserved.
     </p>
     </div>
     <div class="right-col">
       <h1>Contact Us</h1>
       <div class="border">
         <p>Unit 6, 998 North Circular Road, Staples Corner,
          London NW2 7JR
          <br>
          020 8452 5757
          <br>
          projects@cee.uk.com
          </p>
       </div>
     </div>
   </div>
 </footer>
 </div>
</template>

<script>
  export default {
   
  }
</script>

<style scoped>

body{
  margin: 0;
  padding: 0;
  font-family: "Open Sans", sans-serif;
}

footer {
  background: #f1f1f1;
  padding: 90px 0;
}

.footer-container {
  max-width: 1000px;
  margin: auto;
  padding: 0 20;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap:inherit;
}
p{
  display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
}
.border{
  white-space: pre-line;
  display: flex;
    flex-wrap: wrap;
    font-size: 1.1rem;
    margin-bottom: 1.5rem;
        margin-top: .25em;
}
</style>