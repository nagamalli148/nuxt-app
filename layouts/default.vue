<script setup lang="ts">
</script>

<template>
    <div>

        <header>
    <nav> 
        <NuxLink to="/"> NuxtDojo </NuxLink>
        <ul>
            <li><NuxtLink to="/">Home</NuxtLink></li>
            <li><NuxtLink to="/about">About</NuxtLink></li>
            <li><NuxtLink to="/products">Products</NuxtLink></li>
        
        </ul>
    </nav>
</header> 
<!-- output the page ontent -->
<div>
    <slot />
</div>
</div>
</template>


<style scoped>
.router-link-exact-active{
    color:seagreen;
}
</style>