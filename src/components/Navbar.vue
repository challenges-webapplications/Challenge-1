<script setup>

</script>

<template>
  <div>
    <div class="navbar">
      <strong>Challenge 1</strong>
    </div>
    <div class="sidebar">
      <p><a href="#">Option 1</a></p>
    </div>
  </div>

</template>

<style scoped>

.navbar {
  display: flex;
  align-items: center;
  background-color: #333;
  color: white;
  padding: 10px 20px;
}

.sidebar {
  width: 200px;
  height: 100vh;
  background-color: #f4f4f4;
  padding: 20px;
  position: fixed;
  top: 50px; /* below navbar */
  left: 0;
}
</style>