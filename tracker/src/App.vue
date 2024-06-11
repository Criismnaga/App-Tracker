<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <LateralBar />
    </div>
    <div class="column is-three-quarters">
      <MyForm> </MyForm>
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import LateralBar from "./components/LateralBar.vue";
import MyForm from "./components/MyForm.vue";
export default defineComponent({
  name: "App",
  components: {
    LateralBar,
    MyForm,
  },
});
</script>

<style></style>
