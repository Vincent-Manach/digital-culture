<script>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Welcome from './components/Welcome.vue';
import FirstPart from './components/FirstPart.vue';
import SecondPart from './components/SecondPart.vue';
import ThirdPart from './components/ThirdPart.vue';
import FourthPart from './components/FourthPart.vue';
import FifthPart from './components/FifthPart.vue';
import SixthPart from './components/SixthPart.vue';
import SeventhPart from './components/SeventhPart.vue';
import EigthPart from './components/EigthPart.vue';
import NinethPart from './components/NinethPart.vue';
import TenthPart from './components/TenthPart.vue';
import EleventhPart from './components/EleventhPart.vue';
import TwelvethPart from './components/TwelvethPart.vue';

export default {
  components: {
    Welcome, FirstPart, SecondPart, ThirdPart, FourthPart, FifthPart, SixthPart, SeventhPart, EigthPart, NinethPart, TenthPart, EleventhPart, TwelvethPart
  }
}
</script>

<template>
  <div id="intro">
    <Welcome class="fullHeight"/>
    <FirstPart class="fullHeight"/>
  </div>
  <div id="employment">
    <SecondPart class="fullHeight"/>
    <ThirdPart class="fullHeight"/>
    <FourthPart class="fullHeight"/>
    <FifthPart class="fullHeight"/>
  </div>
  <div id="robotics">
    <SixthPart class="fullHeight"/>
    <SeventhPart class="fullHeight"/>
    <EigthPart class="fullHeight"/>
  </div>
  <div id="deepfakes">
    <NinethPart class="fullHeight"/>
    <TenthPart class="fullHeight"/>
    <EleventhPart class="fullHeight"/>
  </div>
  <TwelvethPart class="fullHeight"/>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Jost:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
* {
  margin: 0;
}
#app {
  font-family: Jost;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: white;
}
.fullHeight {
  height: 100vh;
}
.sectionPad {
  padding: 50px;
}
.divided {
  display: flex;
}
.midWidth {
  width: 50%;
}
h1 {
  font-size: 5em;
  transition: 1s;
}
h2 {
  font-size: 2.5em;
}
h3 {
  font-size: 18px;
  font-weight: 400;
}
.sectionMargin {
  padding-left: 50px;
}
.sectionTitle {
  padding-top: 50px;
  margin-bottom: 20px;
}
#intro {
  background: linear-gradient(to bottom, #8E2DE2, #4A00E0);
  border-bottom: 2px solid white;
}
#employment {
  background: linear-gradient(to bottom, #4A00E0, #00b3e0);
  border-bottom: 2px solid white;
}
#robotics {
  background: linear-gradient(to bottom, #00b3e0, #00610d);
  border-bottom: 2px solid white;
}
#deepfakes {
  background: linear-gradient(to bottom, #00610d, #970000);
  border-bottom: 2px solid white;
}
@media screen and (min-width: 1200px) and (max-width: 1500px) {
  h3 {
    font-size: 16px;
  }
}
</style> 
