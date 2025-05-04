<template>
  <div class="flex">
    <input type="email" placeholder="Join Our Mailing List Here" />
    <button>Join</button>
  </div>
</template>

<style>
input {
  padding: 12px 18px;
  border: 1px solid #ccc;
  font-size: 14px;
  width: 250px; /* Adjust width for better form appearance */
  margin-right: 10px; /* Add spacing between the input and button */
}

button {
  padding: 12px 20px;
  background-color: #4caf50;
  color: white;
  border: none;
  font-size: 14px;
  cursor: pointer;
}

button:hover {
  background-color: #45a049;
}

.flex {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  width: 100%;
}

body {
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}

* {
  font-family: Inconsolata-Light;
  box-sizing: border-box;
}
</style>
