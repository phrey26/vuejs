<template>
    <div class="skills">
      <h3>Skills</h3>
      <ul>
        <li v-for="(skill, index) in skills" :key="index">{{ skill }}</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        skills: ["Vue.js", "Node.js", "HTML", "CSS", "JavaScript", "Git"]
      };
    }
  };
  </script>
  