<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere vero esse
      similique reprehenderit pariatur, perspiciatis deserunt natus praesentium
      et expedita libero iusto laborum quaerat officiis ab quis nulla quibusdam
      alias.
    </p>
  </div>
</template>

<script lang="ts" setup>
const { id } = useRoute().params;
definePageMeta({
  layout: "products",
});
</script>

<style></style>
