<template>
  <div class="card">
      <CardTitle/>
      <div>
        <p>Mais baixa</p>
        <p>Atual</p>
        <p>Mais alta</p>
      </div>
      <div>
        <p>
          <span>Data</span>
          <span>Hora</span>
        </p>
        <p>
          <span>Data</span>
          <span>Hora</span>
        </p>
        <p>
          <span>Data</span>
          <span>Hora</span>
        </p>        
      </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

import { CardTitle } from "../molecules";

export default defineComponent({
  components: { CardTitle },
  setup() {
    return {};
  },
});
</script>

<style scoped>
.card{
    width: 100%;
    height: 100%;
    background: royalblue;
    display: flex;
    flex-direction: column;
}
</style>
