<template>
    <h1>Projects Page</h1>
    <RouterLink :to="{ name: '/' }">Go to Home</RouterLink> <span> | </span>
    <RouterLink :to="{ name: '/projects/[id]', params: { id: 1 } }">Go to Project</RouterLink>
</template>

<script setup lang="ts">
</script>