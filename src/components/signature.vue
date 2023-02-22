<template>
  <div class="uk-panel uk-margin uk-text-center">
   Challenge by <a :href="url" target="_blank">{{ site }}</a>. 
   <br />
   Coded by <a :href="github" target="_blank">{{ codedBy }}</a>.
  </div>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  data() {
    return {
      url: 'https://www.frontendmentor.io?ref=challenge',
      site: 'Frontend Mentor',
      codedBy: 'Nouarah Khalfallah',
      github: 'https://github.com/nouarah',
    };
  },
});
</script>
