<template>
  <div class="footer__menu">
    <ul>
      <li v-for="item in items" :key="item.index">
        <router-link :to="item.path" v-if="item.routerLink"> {{ item.title }} </router-link>
        <a :href="item.path" v-text="item.title" v-else/>
      </li>
    </ul>
  </div>
</template>

<script>

export default {
  name: "AppFooterMenu",

  props: {
    title: String,
    items: Array,
  },
};
</script>

<style scoped>

</style>