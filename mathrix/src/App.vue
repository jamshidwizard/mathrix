<script setup>
import { RouterView } from 'vue-router'
import AppHeader from "./components/layouts/AppHeader.vue";
</script>

<template>
  <app-header />
    <main>
        <router-view :key="$route.fullPath" />
    </main>
</template>