<template>
  <ion-app>
    <Nuxt />
  </ion-app>
</template>

<script lang="ts">
  export default {}
  import { applyPolyfills, defineCustomElements } from '@ionic/core/loader';
  (async () => {
    await applyPolyfills();
    await defineCustomElements(window);
  })();
</script>
