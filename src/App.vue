<template>
<div id = "app">
    
  <div class="header">
    <NavBar/>
  </div>
  <div class="body" data-bs-spy="scroll" data-bs-target="#goTop">
      <GioiThieu/>
      <HopTac/>
      <SPDT/>
      <SPHT_DAS/>
      <SKQT/>
      <KNKD/>
      <HDTN/>
      <div id="goTop">
        <a href="#NavBar" id="goTopBtn">
          <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-arrow-up" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M8 15a.5.5 0 0 0 .5-.5V2.707l3.146 3.147a.5.5 0 0 0 .708-.708l-4-4a.5.5 0 0 0-.708 0l-4 4a.5.5 0 1 0 .708.708L7.5 2.707V14.5a.5.5 0 0 0 .5.5"/>
          </svg>
        </a>
      </div>
  </div>
  <div class="footer" style="background-color: dodgerblue;">
      <LH/>
  </div>

</div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import GioiThieu from './components/GioiThieu.vue'
import HopTac from './components/HopTac.vue'
import SPDT from './components/SPDT.vue'
import SPHT_DAS from './components/SPHT_DAS.vue'
import SKQT from './components/SKQT.vue'
import KNKD from './components/KNKD.vue'
import HDTN from './components/HDTN.vue'
import LH from './components/LH.vue'
export default {
  name: 'App',
  components: {
    NavBar,
    GioiThieu,
    HopTac,
    SPDT,
    SPHT_DAS,
    SKQT,
    KNKD,
    HDTN,
    LH

  }
}
</script>

<style>
#goTop {
  color: black; 
  background-color:darkblue;
  position: fixed;
  right: 10px;
  bottom: 10px;


    &:hover {
      opacity: 0.7;
    }
  
}

</style>
