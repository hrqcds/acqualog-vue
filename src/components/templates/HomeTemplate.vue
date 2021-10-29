<template>
  <Header />
  <Card />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Header, Card} from "../organisms";

export default defineComponent({
  components: { Header, Card },
  setup() {
    return {};
  },
});
</script>

<style scoped></style>
