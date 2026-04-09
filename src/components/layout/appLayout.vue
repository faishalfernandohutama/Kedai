<script setup lang="ts">
import { Icon } from '@iconify/vue';

</script>

<template>
    <section>
        <div class="flex flex-col-reverse md:flex-row h-screen bg-gray-50 overflow-hidden">
            <aside class="w-full h-16 bg-white border-t border-gray-200 flex items-center justify-around z-50 shrink-0
            md:w-24 md:h-screen md:flex-col md:justify-start md:border-t-0 md:border-r md:py8">
            <div class="hidden md:flex mb-12">
                  <Icon icon="lucide:flower-2" class="w-8 h-8 text-orange-600" />
            </div>
                <div>
                    <Icon icon="lucide:layout-grid" class="w-6 h-6" />
                </div>
                <div>
                    <Icon icon="lucide:layout-grid" class="w-6 h-6" />
                </div>
                <div>
                    <Icon icon="lucide:layout-grid" class="w-6 h-6" />
                </div>
                <div>
                    <Icon icon="lucide:layout-grid" class="w-6 h-6" />
                </div>
            </aside>
        </div>
    </section>
</template>