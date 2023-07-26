<template>
  <v-row>
    <template v-if="store.products.length === 0">
      <v-col>
        <alert type="error">Problem fetching themes</alert>
      </v-col>
    </template>
  </v-row>
</template>

<script setup>
  // Components
  import ThemeCard from './ThemeCard.vue'

  // Utilities
  import { computed, onMounted } from 'vue'
</script>
