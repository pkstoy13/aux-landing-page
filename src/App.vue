<script setup lang="ts">
//import { /*RouterLink,*/ RouterView } from 'vue-router'
//import HelloWorld from './components/HelloWorld.vue'
import AuxNavbar from './components/AuxNavbar.vue'
import AuxEmailForm from './components/AuxEmailForm.vue'
</script>

<template>
  <header>
    <!--<img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->
    <div class="wrapper">
      <AuxNavbar />
      <AuxEmailForm />
      <!--<HelloWorld msg="You did it!" /> -->

      <!--
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    --></div>
  </header>

  <!--<RouterView />-->
</template>

<style scoped>
@font-face {
  font-family: 'Inconsolata-Light';
  src: url('./assets/Inconsolata-Light.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

* {
  font-family: Inconsolata-Light;
}
</style>

<style>
/* GLOBAL STYLES (not scoped) */
body {
  background-image: url('./assets/aux-bg.svg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  background-color: black;
  animation: bgMove 10s ease-in-out infinite alternate;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
  height: 100vh;
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
