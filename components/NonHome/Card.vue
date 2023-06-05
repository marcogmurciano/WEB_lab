<template>
    <div class="bg flex flex-col gap-2 pb-5 w-[156px]">
        <img :style="`background-image: url('/${img}')`" alt="" class="w-[156px] h-[144px]">
        <div class="mini bold whitespace-break-spaces">{{tit}}</div>
        <div class="mini light">{{text}}</div>
    </div>
</template>


<script setup>
defineProps({
    img: String,
    tit: String,
    text: String,
})
</script>


<style lang="sass" scoped>
    img
        background-size: cover
        background-position: center
</style>