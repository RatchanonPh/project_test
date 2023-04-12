<template>
        <v-radio-group v-model="inline" inline>
            <v-radio label="Halfday" value="radio-1" color="#2E8E69" checked></v-radio>
            <v-radio class="ml-3" label="Fullday" value="radio-2" color="#2E8E69"></v-radio>
            <v-radio class="ml-3" label="Multi-Nights" value="radio-3" color="#2E8E69"></v-radio>
        </v-radio-group>
</template>

<script lang="ts">
export default {
    data () {
      return {
        inline: null,
      }
    },
  }
</script>

<style scoped>

</style>