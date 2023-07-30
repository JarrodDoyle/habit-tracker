<script setup lang="ts">
import Button from "./Button.vue"

defineProps<{
    text?: string,
    icon?: string,
    grey?: boolean,
}>();
</script>


<template>
    <Button :icon="icon" :text="text" :grey="grey" class="w-full" />
</template>