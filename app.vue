
<template>
  <!-- for assistive tech : -->
  <NuxtRouteAnnouncer />
  <div class="min-h-screen text-stone-200 bg-stone-900 p-4">
    <NuxtPage />
  </div>
</template>

<style>
  html {
    font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
    line-height: 1.5;
    font-weight: 400;
  }
</style>

<!-- TODO: edit meta  •  should `<script />` go to top? : -->
<script lang="ts" setup>
  useHead({
    title: 'cubelate ◰',
    meta: [
      { name: 'description', content: 'Nuxt 3' }
    ]
  })
</script>

<!-- TODO: check all the sweet [nuxtr extsn](https://github.com/nuxtrdev/nuxtr-vscode#nuxtr-vscode) features -->

