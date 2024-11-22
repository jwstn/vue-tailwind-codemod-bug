<script setup lang="ts">
import Input from './components/Input.vue'

function foobar() {
    console.log('blur!')
}

</script>

<template>
    <div class="h-dvh w-dvw flex items-center justify-center bg-slate-700">
        <h1>Test</h1>
        <Input @blur=foobar />
    </div>
</template>
