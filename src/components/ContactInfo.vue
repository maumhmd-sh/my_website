<script setup lang="ts">
import { contactItems } from '../../data/contact'
</script>

<template>
  <div class="space-y-2">
    <div
      v-for="(c, i) in contactItems"
      :key="i"
      class="flex flex-col"
    >
      <span class="font-semibold text-gray-800 dark:text-gray-200">
        {{ c.label }}:
      </span>

      <a
        v-if="c.link"
        :href="c.link"
        target="_blank"
        rel="noopener noreferrer"
        class="text-blue-600 dark:text-blue-400 hover:underline"
      >
        {{ c.value }}
      </a>

      <span v-else class="text-gray-700 dark:text-gray-300">
        {{ c.value }}
      </span>
    </div>
  </div>
</template>
