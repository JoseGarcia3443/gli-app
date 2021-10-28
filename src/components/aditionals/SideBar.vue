<template lang="pug">
.sidebar__wrapper.col-12.col-md-4.col-lg-3
</template>


<script lang="ts">
import { defineComponent } from "vue";
import { menus } from "@/mocks/menu";

export default defineComponent({
  name: "SideBar",
  setup() {
    return {
      menus,
    };
  },
});
</script>

<style lang="scss" scoped>
.sidebar__wrapper {
  border-right: 1px solid var(--tertiary);
  min-height: 100vh;
}
</style>
