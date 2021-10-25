<template>
  <pre>{{ numbers }}</pre>
</template>

<script lang="ts">
import { PropType } from 'vue'

export default {
   props: {
      numbers: Array as PropType<Array<{}>> // eslint-disable-line @typescript-eslint/ban-types
   }
 }
</script>