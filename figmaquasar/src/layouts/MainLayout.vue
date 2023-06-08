<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title>figma App</q-toolbar-title>
      </q-toolbar>
    </q-header>
    <div>Hello</div>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from "vue";

const linksList = [];

export default defineComponent({
  name: "MainLayout",

  components: {},

  setup() {
    const leftDrawerOpen = ref(false);

    return {};
  },
});
</script>
