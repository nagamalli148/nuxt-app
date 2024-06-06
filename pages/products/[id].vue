<template>
<div>
<p>Product Details for {{ id }}</p>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas consectetur eaque suscipit optio commodi omnis porro quis soluta, aliquid ab enim excepturi placeat exercitationem non voluptatum cupiditate totam eos laboriosam.</p>
</div>
</template>

<script setup>

const { id }=useRoute().params

</script>

<style scoped>

</style>