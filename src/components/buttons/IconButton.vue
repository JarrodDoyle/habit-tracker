<script setup lang="ts">
import Button from "./Button.vue"

defineProps<{
    icon: string,
    grey?: boolean
    danger?: boolean,
}>();
</script>


<template>
    <Button :icon="icon" :grey="grey" :danger="danger" class="px-2" />
</template>