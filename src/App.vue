<template>
  <div class="w-full min-h-screen">
    <LanguageSwitcher />
    <Home />
    <Education />
    <Skills />
    <Experience />
    <Projects />
    <Resume />
  </div>
</template>

<script lang="ts">
import { defineAsyncComponent } from 'vue';

export default {
  components: {
    Home: defineAsyncComponent(() => import('./components/Home.vue')),
    Resume: defineAsyncComponent(() => import('./components/Resume.vue')),
    Experience: defineAsyncComponent(() => import('./components/Experience.vue')),
    Education: defineAsyncComponent(() => import('./components/Education.vue')),
    Skills: defineAsyncComponent(() => import('./components/Skills.vue')),
    Projects: defineAsyncComponent(() => import('./components/Projects.vue')),
    LanguageSwitcher: defineAsyncComponent(() => import('./components/LanguageSwitcher.vue')),
  }
}
</script>