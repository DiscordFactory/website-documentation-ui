<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <footer class="bg-white dark:bg-gray-800 transition duration-300">
    <div class="max-w-7xl mx-auto py-12 px-4 overflow-hidden sm:px-6 lg:px-8">
      <nav class="-mx-5 -my-2 flex flex-wrap justify-center" aria-label="Footer">
        <div v-for="item in navigation.main" :key="item.name" class="px-5 py-2">
          <a :href="item.href" class="text-base text-gray-500 hover:text-gray-900">
            {{ item.name }}
          </a>
        </div>
      </nav>
      <div class="mt-8 flex justify-center space-x-6">
        <a
          v-for="item in navigation.social"
          :key="item.name"
          :href="item.href"
          rel="nofollow noreferrer noopener"
          target="_blank"
          class="text-gray-400 hover:text-gray-500">
          <span class="sr-only">{{ item.label }}</span>
          <component :is="item.icon" class="h-6 w-6" aria-hidden="true" />
        </a>
      </div>
      <p class="mt-8 text-center text-base text-gray-400">
        &copy; 2021 Baptiste Parmantier - Discord Factory. All rights reserved.
      </p>
    </div>
  </footer>
</template>

<script setup lang="ts">
import { github, twitter } from '../utils/Icons'

const navigation = {
  social: [
    twitter,
    github,
  ],
}
</script>