<template>
    <div class="bg" :class="bgClass">
        <slot />
    </div>
</template>



<script setup>
const bgClass = ref('one')

const one = () => {
    setTimeout(two, 7000);
    bgClass.value= 'two'
};

const two = () => {
    setTimeout(three, 7000);
    bgClass.value= 'three'
};

const three = () => {
    setTimeout(four, 7000);
    bgClass.value= 'four'
};

const four = () => {
    setTimeout(one, 7000);
    bgClass.value= 'one'
};

setTimeout(one, 0);
</script>



<style lang="sass" scoped>
     .one
        background-image: url("/Header_sample.png")
        transition: background-image 5s ease-in-out
    .two
        background-image: url("/Header_2.png")
        transition: background-image 5s ease-in-out
    .three
        background-image: url("/Header_3.png")
        transition: background-image 5s ease-in-out
    .four
        background-image: url("/Header_4.png")
        transition: background-image 5s ease-in-out
</style>
