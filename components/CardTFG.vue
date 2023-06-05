<template>
    <div class="bg" :style="back">
        <div class="text">
            <div class="h4 text-center">
                <slot />
            </div>
            <div class="mini">
                {{ tfg }}
            </div>
            <div class="mini bold">
                {{ autor }}
            </div>
        </div>
    </div>
</template>


<script setup>
const props = defineProps({
    img: String,
    tfg: String,
    autor: String,
 })

 const back =`background-image: url('${props.img}');`
</script>


<style lang="sass" scoped>
    
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
       
</style>