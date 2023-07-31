<script setup lang="ts">
import Panel from "./Panel.vue"
import Button from "./buttons/Button.vue"
import FixedButton from "./buttons/FixedButton.vue"
</script>

<template>
    <div class="p-4">
        <Panel class="w-60">
            <div class="flex flex-col space-y-3 w-full">
                <Button text="Button" />
                <FixedButton text="Fixed Button" />
                <Button icon="settings" text="With Icon" />

                <Button grey text="Grey Button" />
                <FixedButton grey text="Fixed Grey Button" />
                <Button grey icon="settings" text="Grey With Icon" />

                <Button danger text="Danger Button" />
                <FixedButton danger text="Fixed Danger Button" />
                <Button danger icon="settings" text="Danger With Icon" />

                <div class="flex flex-row space-x-3">
                    <Button icon="settings" />
                    <Button grey icon="settings" />
                    <Button danger icon="settings" />
                </div>
            </div>
        </Panel>
    </div>
</template>