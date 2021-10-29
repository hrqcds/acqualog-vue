<template>
  <div class="header">
    <div class="logo-img">
      <img src="../../assets/logo.svg" alt="" />
    </div>
    <NavBar class="nav-bar" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { NavBar } from "../molecules";

export default defineComponent({
  components: { NavBar },
  setup() {
    return {};
  },
});
</script>

<style scoped>
.header {
  width: 100%;
  height: 11vh;
  display: flex;
  justify-content: space-evenly;
  align-items: center;

  box-shadow: 1px 1px 3px rgba(0, 0, 0, 0.8);
}

.logo-img {
  width: 15rem;
  padding-left: 2rem;
}

.nav-bar {
  padding-right: 2rem;
}
</style>
