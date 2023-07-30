<script setup lang="ts">
import Button from "./Button.vue"

defineProps<{
    icon: string,
    grey?: boolean
}>();
</script>


<template>
    <Button :icon="icon" :grey="grey" class="px-2" />
</template>