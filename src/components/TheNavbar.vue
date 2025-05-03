<template>
  <div class="navbar">
    <h2 class="title">
      AUX
    </h2>
    <div class="buttons">
        <p>About</p>
        <p>Team</p>
        <p>Contact</p>
    </div>
  </div>
</template>

<style>
  .navbar {
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  padding: 12px;
  font-size: xx-large;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgba(151, 16, 209, 0.3); /* translucent background */
  backdrop-filter: blur(10px);         /* frosted glass effect */
}

.buttons {
    right: 0;
    margin-right: 16px;
    position: fixed;
    display: flex;
    gap: 24px;
    font-size: x-large;
    cursor: pointer;
  }

.title {
  margin-left: 12px;
  display: flex;
  justify-content: center;
}

</style>
