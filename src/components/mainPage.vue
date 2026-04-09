<script setup>
import { Icon } from "@iconify/vue";
</script>

<template>
  <section class="min-h-screen px-10 py-10 bg-gray-50">
    <div>
      <nav class="flex justify-between items-center">
        
        <div class="flex w-full max-w-xl">
          <div
            class="flex items-center w-full bg-white border border-gray-300 py-2.5 px-5 rounded-full focus-within:border-blue-500 focus-within:ring-2 focus-within:ring-blue-100 transition-all"
          >
            <Icon icon="lucide:search" class="text-gray-400 w-5 h-5 mr-3" />
            <input
              type="text"
              placeholder="Search menu"
              class="w-full bg-transparent border-none outline-none text-gray-700 placeholder-gray-400 text-sm"
            />
          </div>
        </div>

        <div class="flex items-center gap-4 ml-8 cursor-pointer">
          
          <div class="flex flex-col text-right hidden sm:flex">
            <span class="text-sm font-semibold text-gray-800">Faishal Fernando</span>
            <span class="text-xs text-gray-500">Web Developer</span>
          </div>

          <div class="w-10 h-10 rounded-full border-2 border-gray-200 overflow-hidden bg-white flex-shrink-0">
            <img 
              src="https://api.dicebear.com/7.x/notionists/svg?seed=Faishal" 
              alt="Profile" 
              class="w-full h-full object-cover" 
            />
          </div>
          
        </div>

      </nav>
    </div>
  </section>
</template>