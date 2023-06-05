<template>
    <NuxtLink :to="`/${to}`">
        <div class="bg">


<div class="primary cuerpo bop" v-if="!alter">
    <ph-arrow-right :size="16" v-if="icon" />
    <slot />
</div>
<div class="secondary cuerpo bop" v-else>
    <ph-arrow-right :size="16" v-if="icon" />
    <slot />
</div>
</div>
    </NuxtLink>
</template>


<script setup>
 import { PhArrowRight } from "@phosphor-icons/vue";
defineProps({
    alter: Boolean,
    icon: Boolean,
    to: String,
})
</script>


<style lang="sass" scoped>
    .primary
        @apply text-blacko
    .secondary
        @apply text-white
    .bop
        @apply flex items-center
    .bop:hover
        @apply underline
</style>