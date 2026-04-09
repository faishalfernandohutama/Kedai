<script setup lang="ts">
  import { Icon } from "@iconify/vue";
</script>

<template>
  <div
    class="flex flex-col-reverse md:flex-row h-screen bg-gray-50 overflow-hidden"
  >
    <aside
      class="w-full h-16 bg-white border-t border-gray-200 flex items-center justify-around z-50 shrink-0 md:w-24 md:h-screen md:flex-col md:justify-start md:border-t-0 md:border-r md:py-8"
    >
      <div class="hidden md:flex mb-12">
        <Icon icon="lucide:flower-2" class="w-8 h-8 text-mm" />
      </div>
      <!-- menu -->
      <div
        class="flex md:flex-col gap-8 md:gap-6 items-center w-full md:w-auto justify-evenly"
      >
        <div class="p-3 cursor-pointer text-gray-500 hover:text-gray-500 hover:bg-gray-100 rounded-2xl transition-colors">
          <Icon icon="lucide:layout-grid" class="w-6 h-6" />
        </div>
        <div class="p-3 cursor-pointer text-gray-500 hover:text-gray-500 hover:bg-gray-100 rounded-2xl transition-colors">
          <Icon icon="lucide:layout-grid" class="w-6 h-6" />
        </div>
        <div class="p-3 cursor-pointer text-gray-500 hover:text-gray-500 hover:bg-gray-100 rounded-2xl transition-colors">
          <Icon icon="lucide:layout-grid" class="w-6 h-6" />
        </div>
        <div class="p-3 cursor-pointer text-gray-500 hover:text-gray-500 hover:bg-gray-100 rounded-2xl transition-colors">
          <Icon icon="lucide:layout-grid" class="w-6 h-6" />
        </div>
      </div>

      <div class="hidden md:flex mt-auto mb-4 p-3 cursor-pointer text-gray-500 hover:text-gray-800 hover:bg-gray-100 rounded-2xl transition-colors">
        <Icon icon="lucide:layout-grid" class="w-6 h-6" />
      </div>
    </aside>

    <main class="flex-1 overflow-y-auto">
      <slot />
    </main>
  </div>
</template>
