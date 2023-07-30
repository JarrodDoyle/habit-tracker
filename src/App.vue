<script setup lang="ts">
import Sidebar from "./components/Sidebar.vue";
import Playground from "./components/Playground.vue";
</script>

<template>
  <div class="w-screen h-screen bg-slate-950 flex flex-row font-body text-xs text-white">
    <Sidebar />
    <Playground />
  </div>
</template>
