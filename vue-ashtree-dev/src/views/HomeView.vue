<template>
  <body>
    <div>
    <div class="home-content">

      <NavBar/>

      <div class="d-flex justify-content-center align-items-center vh-100">
        <div class="bg-white w-50 p-5 rounded">
          <p class="main-text">
            Hi! i'm Ashton Martinez, a dedicated freelance game and web developer. My journey in the digital domain spans Both passion projects and professional endeavors, with a strong focus on delivering high-quality results in every task
          </p>

          <p class="main-text">If you're seeking a developer with a balance of creativity, technical expertise, and professionalism, I invite you to explore my portfolio or get in touch directly.
</p>
        </div>
      </div>

    </div>
  </div>
  </body>
  
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import NavBar from '@/components/NavBar.vue'; // Adjust the import path based on your project structure

export default defineComponent({
  name: 'HomeView',

  components: {
    NavBar, // Register your NavBar component here
  },

  data() {
    return {
      // Your data properties here
    };
  },

  methods: {
    // Your methods here
  },
});
</script>

<style scoped>

.main-text {
  font-size: 27px;
  letter-spacing: 0.7px;
  line-height: 43px;
}

</style>
