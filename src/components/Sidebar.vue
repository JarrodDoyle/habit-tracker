<script setup lang="ts">
import SidebarButton from "./SidebarButton.vue";
import Button from "./buttons/Button.vue";
</script>

<template>
  <div class="w-52 h-screen border-r border-slate-900 p-3 flex flex-col space-y-3 text-white">
    <div class="font-display text-xl px-1 py-2 self-center">
      <span class="text-emerald-500">Habit</span> Tracker
    </div>
    <hr class="border-slate-900">

    <SidebarButton icon="icons/today-outline-20-white.svg" text="Today" selected />
    <SidebarButton icon="icons/social-leaderboard-outline-20-white.svg" text="Habits" />
    <SidebarButton icon="icons/interests-outline-20-white.svg" text="Categories" />
    <SidebarButton icon="icons/settings-outline-20-white.svg" text="Settings" />

    <hr class="border-slate-900">

    <Button text="Start a new habit" class="self-center" />

    <div class="grow"></div>

    <button
      class="rounded flex flex-row text-slate-600 p-2 space-x-2 items-center hover:bg-slate-900 active:bg-slate-700">
      <img src="icons/bug-report-outline-20-grey.svg" alt="Today Icon" />
      <span>Report a bug</span>
    </button>

    <hr class="border-slate-900">

    <span class="text-slate-600 text-center">v1.2345</span>
  </div>
</template>
