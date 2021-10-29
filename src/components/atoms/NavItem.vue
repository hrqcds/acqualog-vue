<template>
  <router-link :to="to">{{ text }}</router-link>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  props: {
    text: {
      type: String,
      required: true,
    },
    to: {
      type: String,
      required: true,
    },
  },
});
</script>

<style scoped>
a {
  text-decoration: none;
  color: black;
}
</style>
