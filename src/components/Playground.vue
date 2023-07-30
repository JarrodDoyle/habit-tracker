<script setup lang="ts">
import Panel from "./Panel.vue"
import Button from "./buttons/Button.vue"
import FixedButton from "./buttons/FixedButton.vue"
import IconButton from "./buttons/IconButton.vue"
</script>

<template>
    <div class="p-4">
        <Panel class="w-52">
            <div class="flex flex-col space-y-3 w-full">
                <Button text="Button" />
                <FixedButton text="Fixed Button" />
                <Button icon="icons/settings-outline-20-white.svg" text="With Icon" />

                <Button grey text="Grey Button" />
                <FixedButton grey text="Fixed Grey Button" />
                <Button grey icon="icons/settings-outline-20-white.svg" text="Grey With Icon" />

                <IconButton icon="icons/settings-outline-20-white.svg" />
                <IconButton grey icon="icons/settings-outline-20-white.svg" />

            </div>
        </Panel>
    </div>
</template>