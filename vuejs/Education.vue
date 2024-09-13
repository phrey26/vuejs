<template>
    <div class="education">
      <h3>Education</h3>
      <ul>
        <li v-for="(edu, index) in education" :key="index">
          <strong>{{ edu.degree }}</strong> - {{ edu.school }} ({{ edu.year }})
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        education: [
          { degree: "B.S. in Web Development", school: "Holy Angel University", year: "2XXX" },
        ]
      };
    }
  };
  </script>
  