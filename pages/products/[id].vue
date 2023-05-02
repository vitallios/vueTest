<script setup>
const { id } = useRoute().params
definePageMeta({
 layout: 'products'
})
</script>
<template>
 <div>
  <p class="p-5">product for {{ id }}</p>
 </div>
</template>