<script setup lang="ts">
interface Props {
    label: string;
}

const props = defineProps<Props>();
</script>

<template>
    <button>
        {{ props.label }}
    </button>
</template>
