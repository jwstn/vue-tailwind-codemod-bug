<script setup lang="ts">

const emits = defineEmits<{
    (e: 'blur-sm'): void
}>()

</script>
<template>
    <input class="px-4 py-2 bg-white rounded-sm text-base text-lack" placeholder="type here..." @blur="emits('blur-sm')" />
</template>
