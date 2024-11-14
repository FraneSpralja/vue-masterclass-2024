<template>
    <h1>Single Project Page {{ route.params?.id }} </h1>
    <RouterLink to="/projects">Go Back to Projects</RouterLink> <span> | </span>
    <RouterLink :to="`/projects/${+(route.params?.id) + 1}`">Next Project</RouterLink>
</template>

<script setup lang="ts">
import { useRoute } from 'vue-router';

const route = useRoute()
</script>