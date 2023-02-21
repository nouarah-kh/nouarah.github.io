<template>
  <div class="attribution">
    <span>Challenge by &nbsp;</span>
    <a :href="frontMentorUrl" target="_blank"> Frontend Mentor</a>. Coded by
    <a href="#">{{ codedBy }}</a
    >.
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  data() {
    return {
      frontMentorUrl: 'https://www.frontendmentor.io?ref=challenge',
      codedBy: 'Nouarah Khalfallah',
    };
  },
});
</script>
