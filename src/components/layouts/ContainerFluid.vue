<template lang="pug">
.col-12.col-md-8.col-lg-9
    slot
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'ContainerFluid'
})
</script>
