<script setup lang="ts">
import { type SubscribeFormBlock } from '~/types';

interface Props {
    payload: SubscribeFormBlock,
};

defineProps<Props>();
</script>

<template>
<section>
    <BaseForm />
</section>
</template>

<style scoped lang="scss">
</style>
