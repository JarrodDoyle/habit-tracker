<script setup lang="ts">
</script>

<template>
  <div class="w-52 h-screen border-r border-slate-900 p-3 flex flex-col space-y-3 text-white">
    <div class="font-display text-xl px-1 py-2 self-center"><span class="text-emerald-500">Habit</span> Tracker</div>
    <hr class="border-slate-900">

    <!-- TODO: Extract to a component -->
    <button
      class="bg-slate-800 rounded flex flex-row text-white p-2 space-x-2 items-center hover:bg-slate-900 active:bg-slate-700">
      <img src="icons/today-outline-20-white.svg" alt="Today Icon" />
      <span class="font-body text-xs">Today</span>
    </button>

    <button class="rounded flex flex-row text-white p-2 space-x-2 items-center hover:bg-slate-900 active:bg-slate-700">
      <img src="icons/social-leaderboard-outline-20-white.svg" alt="Today Icon" />
      <span class="font-body text-xs">Habits</span>
    </button>

    <button class="rounded flex flex-row text-white p-2 space-x-2 items-center hover:bg-slate-900 active:bg-slate-700">
      <img src="icons/interests-outline-20-white.svg" alt="Today Icon" />
      <span class="font-body text-xs">Categories</span>
    </button>

    <button class="rounded flex flex-row text-white p-2 space-x-2 items-center hover:bg-slate-900 active:bg-slate-700">
      <img src="icons/settings-outline-20-white.svg" alt="Today Icon" />
      <span class="font-body text-xs">Settings</span>
    </button>

    <hr class="border-slate-900">

    <button class="self-center w-fit bg-emerald-500 rounded px-4 py-2 font-body text-slate-950 text-xs">
      Start a new habit
    </button>

    <div class="grow"></div>

    <button
      class="rounded flex flex-row font-body text-xs text-slate-600 p-2 space-x-2 items-center hover:bg-slate-900 active:bg-slate-700">
      <img src="icons/bug-report-outline-20-grey.svg" alt="Today Icon" />
      <span>Report a bug</span>
    </button>

    <hr class="border-slate-900">

    <span class="text-slate-600 font-body text-xs text-center">v1.2345</span>
  </div>
</template>
