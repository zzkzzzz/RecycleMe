<template>
  <!-- See class applied to the html tag in index.html for sticky navbar -->
  <nav id="nav" class="navbar is-fixed-top is-white" role="navigation">
    <div class="navbar-brand">
      <router-link :to="{ name: 'home' }" class="navbar-item">
        <img
          src="https://cdn-icons-png.flaticon.com/512/346/346195.png"
          alt="Logo"
        />
      </router-link>

      <!-- Using <a> instead of button as it does not need an icon and dont have the inverted colors on click behaviour -->
      <a
        role="button"
        class="navbar-burger"
        :class="{ 'is-active': showMobileMenu }"
        aria-label="menu"
        data-target="navbar-menu"
        @click="showMobileMenu = !showMobileMenu"
      >
        <!-- 3 empty span tags to show the burger menu icon -->
        <span></span>
        <span></span>
        <span></span>
      </a>
    </div>

    <div
      class="navbar-menu has-text-right"
      :class="{ 'is-active': showMobileMenu }"
    >
      <div class="navbar-end">
        <router-link
          v-for="(menuItem, i) in menuItems"
          :key="i"
          :to="menuItem.link"
          class="navbar-item"
        >
          <span @click="showMobileMenu = false">{{ menuItem.name }}</span>
        </router-link>
      </div>
    </div>
  </nav>

  <br />
</template>

<script lang="ts">
export default {
  name: "Navbar",
  data() {
    return {
      showMobileMenu: false,

      // @todo Add menu items as needed
      menuItems: [
        { name: "Home", link: "/" },
        { name: "Recycle", link: "/tree" },
        { name: "Achievement", link: "/profile" },
        { name: "Contact us", link: "/contact" },
      ],
    };
  },
};
</script>

<style scoped>
/* Gives the nav bar a white fill background and a super thin and light bottom underline to give visual seperation from the content */
#nav {
  background: white;
  border-bottom: 1px solid rgb(231, 231, 231);
}
</style>
