<template>
    <div class="bg relative flex flex-col justify-end" :style="back">
        <div class="text absolute top-0 left-0">
            <div class="cuerpo p-6">
                <slot />
            </div>
        </div>
        <div class="down bg-white flex flex-col items-center gap-1 px-5 py-2">
            <div class="flex flex-col">
                <div class="up flex gap-1">
                <ph-calendar-blank :size="20" color="717171"/>

                <span>{{ date }}</span>
                <span class="pl-3">{{ hour }}</span>
            </div>
            <div class="h4 uppercase">{{ name }}</div>
            </div>
        </div>
    </div>
</template>


<script setup>
 import { PhCalendarBlank } from "@phosphor-icons/vue";
 const props = defineProps({
    img: String,
    name: String,
    hour: String,
    date: String,
 })

 const back =`background-image: url('${props.img}');`
</script>


<style lang="sass" scoped>
    .up
        @apply text-gray4
    .text
        @apply text-white h-full w-full bg-blacko flex flex-col justify-center items-center gap-2
        opacity: 0
        transition: opacity 0.3s ease
    .text:hover
        opacity: 1
        transition: opacity 0.3s ease
    .bg
      
        background-repeat: no-repeat
        background-position: center
        background-size: cover
        height: 372px

</style>