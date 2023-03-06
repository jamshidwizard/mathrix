<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <main>
        <router-view :key="$route.fullPath" />
    </main>
</template>