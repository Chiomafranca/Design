<template>
  <div>
    <router-view />
    <FigmaApp />
  </div>
</template>

<script>
import { defineComponent } from "vue";
import FigmaApp from "./pages/FigmaApp.vue";

export default defineComponent({
  name: "App",
  components: { FigmaApp },
});
</script>
