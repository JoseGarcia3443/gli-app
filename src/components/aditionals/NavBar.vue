<template lang="pug">
nav
  v-container
    .row.no-gutters
</template>


<script lang="ts">
import { defineComponent } from "vue";
import { VContainer } from "@/components";
export default defineComponent({
  name: "NavBar",
  components: {
    VContainer,
  },
});
</script>

<style lang="scss" scoped>
nav {
  background-color: var(--secondary);
  padding: 10px;
}
</style>