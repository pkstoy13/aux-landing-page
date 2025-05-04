<template>
  <div class="navbar">
    <h1 class="title">AUX</h1>
    <div class="buttons">
      <p>About</p>
      <p>Team</p>
      <p>Contact</p>
    </div>
  </div>
</template>

<style scoped>
.navbar {
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgba(0, 0, 0, 0.3); /* translucent background */
  backdrop-filter: blur(10px); /* frosted glass effect */
}

.buttons {
  right: 0;
  position: fixed;
  display: flex;
  gap: 24px;
  margin-right: 12px;
  font-size: large;
  cursor: pointer;
}

.title {
  margin-left: 12px;
  display: flex;
  justify-content: center;
}
</style>
