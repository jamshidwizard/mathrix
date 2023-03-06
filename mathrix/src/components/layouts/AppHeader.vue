<template>
  <header class="header">
      <div class="container d-flex align-items-center">
          <icon-logo />
          <div class="header__search d-flex align-items-center ms-auto me-3">
            <icon-search />
            <input type="text" placeholder="Find what interests you"/>
          </div>
          <div class="header__terminal me-3">
            <select class="form-select" aria-label="Default select example">
              <option selected>Terminal ES</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
          </div>
          <div class="header__premium me-3">
            <button class="btn text-secondary">Get Premium</button>
          </div>
          <div class="header__actions">
              <button class="header__actions--user btn me-3">
                <icon-user />
              </button>
            <button class="header__actions--notification btn">
              <icon-notification />
            </button>
          </div>
      </div>
  </header>
</template>

<script>
import IconLogo from "../icons/IconLogo.vue";
import IconSearch from "../icons/IconSearch.vue";
import IconUser from "../icons/IconUser.vue";
import IconNotification from "../icons/IconNotification.vue";
export default {
  name: "AppHeader",
  components: { IconNotification, IconUser, IconSearch, IconLogo }
};
</script>

<style scoped>

</style>