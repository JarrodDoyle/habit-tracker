<script setup lang="ts">
defineProps<{
    text?: string,
    icon?: string,
    selected?: boolean,
}>();
</script>

<template>
    <button :class="{ 'bg-slate-800': selected }"
        class="rounded flex flex-row text-white p-2 space-x-2 items-center hover:bg-slate-900 active:bg-slate-700">
        <img v-if="icon" :src="icon" alt="Icon" />
        <span v-if="text">{{ text }}</span>
    </button>
</template>