<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
import { Page } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
    components: {
      Page,
    }
});
</script>

<template>
  <div id="app">
    <Page />
  </div>
</template>
