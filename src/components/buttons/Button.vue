<script setup lang="ts">
defineProps<{
    text?: string,
    icon?: string,
    grey?: boolean,
}>();
</script>

<template>
    <button :class="{
        'bg-slate-700 hover:bg-slate-800 active:bg-slate-600 text-white': grey,
        'bg-emerald-500 hover:bg-emerald-600 active:bg-emerald-400': !grey
    }" class="w-fit justify-center items-center rounded flex flex-row text-slate-950 px-4 py-2 space-x-2 ">
        <img v-if="icon" :src="icon" alt="Icon" />
        <span v-if="text">{{ text }}</span>
    </button>
</template>