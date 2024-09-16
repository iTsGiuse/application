<script setup>
import Header from './components/Header.vue'
import Info from './components/Info.vue'
import Progetti from './components/Progetti.vue'
import Footer from './components/Footer.vue'
</script>

<template>
    <Header></Header>
    <main>
      <Info></Info>
      <Progetti></Progetti>
    </main>
    <Footer></Footer>
</template>

<style>
  *{
    font-family: "Nunito Sans", system-ui;
    font-style: normal;
  }
</style>
