<template>
    <div>
<!-- card start -->
<div v-for="monkey in products" :key="monkey.id">
     <card :props="monkey"/>
</div>
<!-- card start end -->
    </div>
</template>

<script setup>
 const{ data:product} = usefetch ('https://fakestoreapi.com/products/1');

</script>

<style lang="scss" scoped>

</style>