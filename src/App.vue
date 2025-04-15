<script setup>
import Navbar from "@/components/Navbar.vue";
import FooterComponent from "@/components/Footer-component.vue";
import Card from "@/components/card.vue"; // Necesitamos ref para trabajar con variables reactivas

</script>

<template>
  <title>Challenge 1</title>
  <div>
    <navbar/>
    <card/>
    <footer-component/>
  </div>
</template>

<style scoped>
html, body {
  margin: 0;
  padding: 0;
  height: 100%;
  font-family: Arial, sans-serif;
}

 div {
  display: grid;
  min-height: 100dvh;
  grid-template-rows: auto 1fr auto;
}
.content {
  flex: 1;
  padding: 20px;
}
</style>
