<template>
    <div class="profile">
      <h2>{{ name }}</h2>
      <p>{{ title }}</p>
      <p>{{ description }}</p>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        name: "Sir Humphrey Huey M. Huet",
        title: "Full Stack Web Developer",
        description: "Passionate about building scalable web applications and working with modern technologies."
      };
    }
  };
  </script>
  
  <style scoped>
  .profile {
    text-align: center;
  }
  </style>
  