<script setup lang="ts">
defineProps<{
    text?: string,
    icon?: string,
    grey?: boolean,
    danger?: boolean,
}>();
</script>

<template>
    <button :class="{
        'bg-slate-700 hover:bg-slate-800 active:bg-slate-600 text-white': grey,
        'bg-emerald-500 hover:bg-emerald-600 active:bg-emerald-400': !grey,
        'bg-red-600 hover:bg-red-700 active:bg-red-500 text-white': danger,
        'px-4': text
    }" class="w-fit justify-center items-center rounded flex flex-row text-slate-950 p-2 space-x-2 ">
        <span v-if="icon" class="material-symbols-outlined">{{ icon }}</span>
        <span v-if="text">{{ text }}</span>
    </button>
</template>