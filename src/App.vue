<template>
    <div class="uk-container">
    <card />
    <signature />
  </div> 
</template>

<script>

import { defineComponent } from 'vue';
import card from '@/components/card.vue';
import signature from '@/components/signature.vue';

export default defineComponent({
  name: 'App',
  components: {
    card,
    signature,
  },
});
</script>

<style lang="less">
  @import "../node_modules/uikit/src/less/uikit.theme.less";
</style>