<template>
    <div :class="props.btn" class="mini bold px-4 py-2 rounded flex gap-1 items-center">
        <slot /> <ph-caret-right :size="16" weight="bold" v-if="props.icon" />
    </div>
</template>


<script setup>
import { PhCaretRight } from "@phosphor-icons/vue";
const props = defineProps({
    btn: String,
    icon: Boolean,
})

</script>


<style lang="sass" scoped>
    .primary
        @apply bg-primary text-blacko
    .secondary
        @apply text-white bg-blacko
    .tertiary
        @apply bg-transparent text-white border-white border-2
    .disabled
        @apply text-white bg-gray4
    .primary:hover
        @apply shadow-hover
    .secondary:active
        @apply bg-white text-blacko
    .tertiary:hover
        @apply bg-white text-blacko
   
    
</style>