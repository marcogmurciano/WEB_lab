<template>
    <div class="bg flex justify-between items-center">
        <div class="h2 uppercase">
            <slot />
        </div>
        <MyLink :icon="true" :alter="false">Ver más</MyLink>
    </div>
</template>


<script setup>
import { PhArrowCircleRight } from "@phosphor-icons/vue";

</script>


<style lang="sass" scoped>

</style>