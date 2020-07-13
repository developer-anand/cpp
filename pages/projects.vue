<template>
  <div class="container">

    
      <main>
           <img 
        src="~/assets/projects.png" />
      </main>
      
<br><br>
    <div class="holdingcontainer">
      <div class="internalcontainerL">
        <h1>Sample Project-1</h1>
        <img class="dasimages" 
        src="~/assets/project.png" 
        width="100%"/>
        Colfix, needed to retrofit air conditioning to eight offices on the 1st floor. Turning to the expertise of EJ Fidgeon who recommended the Hi-Velocity System as the ideal solution. The Hi-Velocity System offers draught free air flow, even temperatures from floor to ceiling, air filtration and fresh air.</div>      <div class="internalcontainerM">
        <h1>Sample Project-2</h1>
        <img class="dasimages" 
        src="~/assets/project.png" 
        width="100%"/>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>

      <div class="internalcontainerR">
        <h1>Sample Project-3</h1>
        <img class="dasimages" src="~/assets/project.png" width="100%"/>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>
    </div>
      
    </div>
    

</template>

<script lang="ts">
import Vue from 'vue'
//import logo from './components/Logo.vue'
export default Vue.extend({
  components: {
    //Logo
  },
}
)
</script>
 <style scoped>
  
  
.container {
  width: 80%;
  margin: 0 auto;
  height: auto;
}
    main {
      width: 100%;
      height: auto;
      display: flex;
      flex-direction: column;
      align-items: center;
    
    }
    *, :after, :before {
    box-sizing: border-box;
    margin: 0;
}

div{
  display: block;
}
    .holdingcontainer{
      max-width: 100%;
      display: flex;
      background: #fff;
      padding: 50px;
      box-sizing: border-box;
      flex-direction: row;
    }

    .internalcontainerL{
      flex: 1;
      background: red;
      padding: 30px;
      font-size: 12px;
      font-family: 'Roboto', sans-serif;
      margin: 3px;
    }

    .internalcontainerM{
      flex: 1;
      background: pink;
      padding: 30px;
      font-size: 12px;
      font-family: 'Roboto', sans-serif;
      margin: 3px;
    }

    .internalcontainerR{
      flex: 1;
      background: cyan;
      padding: 30px;
      font-size: 12px;
      font-family: 'Roboto', sans-serif;
      margin: 3px;
    }

    @media screen and (max-width: 768px){
      .holdingcontainer{
        flex-direction: column-reverse;
      }
    }
    </style>
  