<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div class="relative">
    <div class="absolute inset-0 flex items-center" aria-hidden="true">
      <div class="w-full border-t border-gray-300" />
    </div>
    <div class="relative flex justify-center">
      <span class="px-2 text-sm text-gray-500">
        {{ text }}
      </span>
    </div>
  </div>
</template>


<script setup lang='ts'>
import { defineProps } from 'vue'

type Props = {
  text: string
}
defineProps<Props>()
</script>