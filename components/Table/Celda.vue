<template>
    <div class="bg flex justify-between py-3 pl-5 pr-2 border-gray1 border-y" :class="'bg-' + props.color">
        <div class="mini" :class="textClass">
            <slot />
        </div>
        <div class="mini" :class="textClass" v-if="props.hasNum">
            {{ props.num }}
        </div>
        <div class="other" v-else :class="'text-'+ props.color">
            .
        </div>
    </div>
</template>


<script setup>
    const props = defineProps({
        num: Number,
        Bold: String,
        hasNum: Boolean,
        color: String
    })
    let textColor = ''
    if (props.color == 'blacko') {
        textColor = 'white'
    } else {
        textColor= 'blacko'
    }
    const textClass = `text-${textColor} ${props.Bold}`
</script>


<style lang="sass" scoped>

</style>