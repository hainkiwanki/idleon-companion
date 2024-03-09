<script setup lang="ts">
import { useQuasar } from 'quasar';

const $q = useQuasar();

function onButtonClick() {
    $q.dark.toggle();
}
</script>

<template>
    <button type="button" @click="onButtonClick">Button</button>
</template>

<style scoped></style>
