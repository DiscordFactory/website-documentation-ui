<template>
  <div class="relative py-16 bg-white dark:bg-gray-900">
    <div class="hidden absolute top-0 inset-x-0 h-1/2 lg:block" aria-hidden="true" />
    <div class="max-w-7xl mx-auto lg:bg-transparent lg:px-8">
      <div class="lg:grid lg:grid-cols-12">
        <div class="relative z-10 lg:col-start-1 lg:row-start-1 lg:col-span-4 lg:py-16 lg:bg-transparent">
          <div class="max-w-md mx-auto px-4 sm:max-w-3xl sm:px-6 lg:max-w-none lg:p-0">
            <div class="bg-blue-900 rounded-xl aspect-w-10 aspect-h-6 sm:aspect-w-2 sm:aspect-h-1 lg:aspect-w-1.5">
              <img class="rounded-md object-cover" src="../assets/discord-banner.jpg" alt="Workflow" />
            </div>
          </div>
        </div>

        <div class="relative lg:col-start-3 lg:row-start-1 lg:col-span-10 lg:rounded-3xl lg:grid lg:grid-cols-10 lg:items-center">
          <div class="hidden absolute inset-0 overflow-hidden rounded-3xl lg:block" aria-hidden="true">
            <svg class="absolute bottom-full left-full transform translate-y-1/3 -translate-x-2/3 xl:bottom-auto xl:top-0 xl:translate-y-0" width="404" height="384" fill="none" viewBox="0 0 404 384" aria-hidden="true">
              <defs>
                <pattern id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                  <rect x="0" y="0" width="4" height="4" class="text-gray-700 dark:text-gray-700 opacity-50" fill="currentColor" />
                </pattern>
              </defs>
              <rect width="404" height="384" fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)" />
            </svg>
            <svg class="absolute top-full transform -translate-y-1/3 -translate-x-1/3 xl:-translate-y-1/2" width="404" height="384" fill="none" viewBox="0 0 404 384" aria-hidden="true">
              <defs>
                <pattern id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                  <rect x="0" y="0" width="4" height="4" class="text-gray-900 dark:text-gray-200" fill="currentColor" />
                </pattern>
              </defs>
              <rect width="404" height="384" fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)" />
            </svg>
          </div>
          <div class="relative max-w-md mx-auto py-12 px-4 space-y-6 sm:max-w-3xl sm:py-16 sm:px-6 lg:max-w-none lg:p-0 lg:col-start-4 lg:col-span-6">
            <h2 class="text-3xl font-extrabold dark:text-white" id="join-heading">Join us on discord</h2>
            <p class="text-lg dark:text-white">
              Do you need help, want to discuss the project or participate in the adventure by suggesting improvements ? Join us at.
            </p>
            <LinkExternal
              url="https://discord.gg/tQebEww8zG"
              class="block w-full py-3 px-5 text-center dark:bg-gray-600 border border-transparent rounded-md shadow-md text-base font-medium text-gray-700 hover:bg-gray-50 dark:text-white sm:inline-block sm:w-auto">
              Discover
            </LinkExternal>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script setup lang="ts">
import { ExternalLinkIcon } from '@heroicons/vue/solid'
import LinkExternal from './LinkExternal.vue'
</script>