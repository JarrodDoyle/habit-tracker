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

    <SidebarButton icon="today" text="Today" selected />
    <SidebarButton icon="social_leaderboard" text="Habits" />
    <SidebarButton icon="interests" text="Categories" />
    <SidebarButton icon="settings" text="Settings" />

    <hr class="border-slate-900">

    <Button text="Start a new habit" class="self-center" />

    <div class="grow"></div>

    <SidebarButton icon="bug_report" text="Report a bug" class="text-slate-600 hover:text-white" />

    <hr class="border-slate-900">

    <span class="text-slate-600 text-center">v1.2345</span>
  </div>
</template>
