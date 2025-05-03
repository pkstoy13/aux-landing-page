<script setup lang="ts">
//import { /*RouterLink,*/ RouterView } from 'vue-router'
//import HelloWorld from './components/HelloWorld.vue'
import TheNavbar from './components/TheNavbar.vue'


</script>

<template>
  <header>
    <!--<img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->
    <div class="wrapper">
      <TheNavbar/>
      <!--<HelloWorld msg="You did it!" /> -->

      <!--
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    -->
    </div>
  </header>

  <!--<RouterView />-->
</template>

<style scoped>

  @font-face {
    font-family: 'Oxanium';
    src: url('./assets/Oxanium-VariableFont_wght.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
  }

  * {
    font-family: Oxanium;
  }

</style>

<style>
/* GLOBAL STYLES (not scoped) */
body {
  background-image: url('./assets/aux-background.svg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  animation: bgMove 5s ease-in-out infinite alternate;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}

@keyframes bgMove {
  0% {
    background-position: 0% 0%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 100%;
  }
}

</style>
