<template lang="pug">
#app.row.no-gutters
  v-side-bar
  v-container-fluid
    v-nav-bar
    router-view
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { VContainer, VSideBar, VNavBar, VContainerFluid } from "@/components";

export default defineComponent({
  components: {
    VContainer,
    VContainerFluid,
    VSideBar,
    VNavBar,
  },
});
</script>

<style lang="scss">
@import "./style/simple-grid/bootstrap-grid.scss";
@import "./style/variables.scss";
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@600&family=Mulish:wght@700&family=Open+Sans:wght@400;600&family=Roboto:wght@400;500&display=swap");

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
}
</style>
