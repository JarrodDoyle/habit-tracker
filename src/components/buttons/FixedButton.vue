<script setup lang="ts">
import Button from "./Button.vue"

defineProps<{
    text?: string,
    icon?: string,
    grey?: boolean,
    danger?: boolean,
}>();
</script>


<template>
    <Button :icon="icon" :text="text" :grey="grey" :danger="danger" class="w-full" />
</template>