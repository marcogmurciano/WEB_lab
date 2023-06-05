<template>
    <div class="bg shadow-hover" :style="back">
        <div class="text">
            <div class="mini bold text-gray4">
                Grado en diseño
            </div>
            <div class="h4">
                <slot />
            </div>
        </div>
    </div>
</template>


<script setup>
const props = defineProps({
    img: String,
 })

 const back =`background-image: url('${props.img}');`
</script>


<style lang="sass" scoped>
    .bg
        @apply flex flex-col justify-end
        background-repeat: no-repeat
        background-position: center
        background-size: cover
        height: 248px

    .bg:hover
        .text
            opacity: 0
            transition: opacity 0.3s ease
            
    .text
        @apply flex flex-col gap-1 py-4 px-6 bg-white
        opacity: 1
        transition: opacity 0.3s ease
</style>