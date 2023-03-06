<script setup>
import { RouterView } from 'vue-router'
import AppHeader from "./components/layouts/AppHeader.vue";
import AppFooter from "./components/layouts/AppFooter.vue";
</script>

<template>
  <app-header />
    <main>
        <router-view :key="$route.fullPath" />
    </main>
  <app-footer />
</template>