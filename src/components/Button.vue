<script setup lang="ts">
defineProps<{
    text?: string,
    icon?: string,
}>();
</script>

<template>
    <button
        class="w-fit bg-emerald-500 rounded flex flex-row text-slate-950 px-4 py-2 space-x-2 items-center hover:bg-emerald-600 active:bg-emerald-400">
        <img v-if="icon" :src="icon" alt="Icon" />
        <span v-if="text" class="font-body text-xs">{{ text }}</span>
    </button>
</template>