<script setup lang="ts">
import Input from './components/Input.vue'

function foobar() {
    console.log('blur-sm!')
}

</script>

<template>
    <div class="h-dvh w-dvw flex items-center justify-center bg-slate-700 flex-col gap-4">
        <h1 class="text-3xl text-white">Test Input</h1>
        <Input @blur=foobar />
    </div>
</template>
