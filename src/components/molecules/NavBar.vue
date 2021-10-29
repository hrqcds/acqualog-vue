<template>
  <nav class="nav-bar">
    <ul>
      <li>
        <NavItem to="/" text="Dashboard" />
      </li>
      <li>
        <NavItem to="/" text="Relatórios" />
      </li>
      <li>
        <NavItem to="/" text="Gráficos" />
      </li>
    </ul>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { NavItem } from "../atoms";

export default defineComponent({
  components: { NavItem },
});
</script>

<style scoped>
.nav-bar {
  width: 100%;
  display: flex;
  justify-content: end;
}

.nav-bar ul {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

.navbar ul,
li {
  padding: 0.7rem;
  background: rgba(255, 255, 255, 0.6);
  border-radius: 8px;
  box-shadow: 1px 1px 8px rgba(0, 0, 0, 0.2);
}

.navbar ul,
li:hover {
  padding: 0.7rem;
  background: cornflowerblue;
  border-radius: 8px;
  box-shadow: 1px 1px 8px rgba(0, 0, 0, 0.2);
  color: white;
  cursor: pointer;
}
</style>
