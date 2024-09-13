<template>
    <div class="experience">
      <h3>Experience</h3>
      <ul>
        <li v-for="(exp, index) in experiences" :key="index">
          <strong>{{ exp.jobTitle }}</strong> at {{ exp.company }} ({{ exp.years }})
          <p>{{ exp.description }}</p>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        experiences: [
          {
            jobTitle: "Frontend Developer",
            company: "Tech Solutions Inc.",
            years: "2025-present",
            description: "Developed interactive user interfaces with Vue.js."
          },
          {
            jobTitle: "Full Stack Developer",
            company: "WebApps Co.",
            years: "2025-Present",
            description: "Led the development of scalable web applications using Node.js and Vue.js."
          }
        ]
      };
    }
  };
  </script>
  