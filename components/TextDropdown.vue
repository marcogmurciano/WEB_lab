<template>
    <div class="bg flex flex-col">
        <div class="top flex gap-2" @click="voltereta()">
            <div :class="props.typ">
                {{ props.tit }}
            </div>
            <div class="cont" :class="classimg">
                <ph-caret-up :size="20" />
            </div>
        </div>
        <div class="text" :class="classimg">
            <div class="cuerpo ">
                <slot />
            </div>
        </div>
    </div>
</template>


<script setup>

const props = defineProps({
    tit: String,
    typ: String,
})

import { ref } from 'vue';
import { PhCaretUp } from "@phosphor-icons/vue";


const classimg = ref('')

const voltereta = () => {
    if (classimg.value == 'opened') {
        classimg.value = ''
    } else {
        classimg.value = 'opened'
    }
}

</script> 


<style lang="sass" scoped>
    .cont.opened 
        transform: rotate(180deg)
        transition: transform 0.3s ease-out
    

    .cont 
        transition: transform 0.3s ease-out
    
        

    .text
        @apply hidden
    .text.opened
        @apply flex px-14 py-3

</style>