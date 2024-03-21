<script setup lang="ts">
const route = useRoute()
definePageMeta({
  layout: "default",
})

</script>

<template>
  <div class="">
    <Home />
    <Predict />
    <EarlyPredict />
    <Contact />
  </div>
</template>
