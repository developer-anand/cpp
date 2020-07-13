<template>
  <div class="container">
    <img src="~/assets/carrers.png" />
    <main>
      
    <div class="current">
      <br>
      <br>
      <h1 class="title">
        Current Opening
      </h1>
      <br>
      <br>
      <div class="columns">
        <div class="column">
          <div class="column-wrapper">
            <h1>
              Mechanical Supervisor
            </h1>
            <div class="job-des">
              <p class="data">
                
                      We are looking for enthusiastic, high energy Mechanical
                      Supervisors. Someone who has trade experience,
                      understands our industry complexities when it comes to
                      coordination, general on-site issues, bringing solutions
                      to problems to the table for a swift and economical
                      resolution. Record keeping being key, but also
                      supporting our Project Managers on site.
                    
              </p>
            </div>
          </div>
        </div>

        <div class="column">
          <div class="column-wrapper">
            <h1>
              Electricion
            </h1>
            <div class="job-des">
              <p class="data">
                      We are a growing company in need of qualified
                      electricians for a permanent full-time position to carry
                      out New Installations within the Greater London area.
                      The applicant is expected to have at least 2 years
                      experience post qualification within the commercial
                      industry. All applicants are required to carry the
                      appropriate safety cards.
              </p>
            </div>
          </div>
        </div>
        

      </div>
    </div>
    <br>
    <br>
    <h1>
      Applying for a Job Opening
    </h1>
    <p>
      If you think you fit the bill for any of the current job openings at Control Electrical Engineering, this is what you need to send an email at info@cee.uk.com 
      in with the subject line of the position you are applying for
    </p>
    <h3>
      Attach an updated copy of your CV.
    </h3>
      </main>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
//import logo from './components/Logo.vue'
export default Vue.extend({
  
})
</script>

<style  scoped>
*, :after, :before {
    box-sizing: border-box;
    margin: 0;
}

div{
  display: block;
}

.columns{
      margin-bottom: -.75rem;
     margin-left: -.75rem;
    margin-right: -.75rem;
    margin-top: -.75rem;
}
.column{
  display: block;
    flex-basis: 0;
    flex-grow: 1;
    flex-shrink: 1;
    padding: .75rem;
}
.current .column-wrapper{
      padding: 20px;
      border: 2px solid #d5160c;
     max-width: 2000px;
      margin: auto;

  
  justify-content:space-between;
  
  flex-wrap:wrap;
}


.current .job-des{
      font-size: 1.25rem;
}

  .title{
    font-size: 1.7rem;
    margin-bottom: 1.5rem;
    font-weight: 700;
    letter-spacing: 2px;
    font-family: Spartan;
    text-align: center;
}
p .data{
  display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
   
}
p{
  display: flex;
  justify-content: center;
}


</style>