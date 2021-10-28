<template lang="pug">
.container
    slot
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'VContainer'
})
</script>
