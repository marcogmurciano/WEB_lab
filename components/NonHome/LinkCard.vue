<template>
    <div class="bg-gray3 flex flex-col justify-center p-12 gap-3 w-fit">
        <div class="h4 text-center">
            {{ tit }}
        </div>
        <div class="flex flex-col gap-2 justify-center items-center">
            <MyLink class="text-center"> link</MyLink>
            <MyLink class="text-center"> linktggggggg</MyLink>
            <MyLink class="text-center"> link</MyLink>
            <MyLink class="text-center"> link</MyLink>
        </div>

    </div>
</template>


<script setup>
defineProps({
    tit: String,
})
</script>


<style lang="sass" scoped>

</style>