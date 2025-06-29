<script setup lang="ts">
//import { RouterLink, RouterView } from 'vue-router'
import { useColorMode } from '@vueuse/core';
import { SidebarProvider } from "@/components/ui/sidebar";
import AppSidebar from "@/components/AppSidebar.vue";

//const mode =
useColorMode();
</script>

<template>
  <SidebarProvider>
    <AppSidebar />

    <main class="w-full h-screen">
      <RouterView />
    </main>
  </SidebarProvider>


</template>

<style scoped></style>
