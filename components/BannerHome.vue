<template>
    <DynamicBg class="bg-blacko bg">
        <div class="text flex flex-col gap-8">
            <div class="display text-white">Descubre la E/S/D/</div>
            <div class="body text-white">
                Si tienes inquietud y creatividad, visualizas los problemas y buscas soluciones. Si entiendes el mundo que
                te rodea y quieres cambiarlo. Estudiar diseño con nosotros es tu manera de lograrlo.
            </div>
            <FormInput />
        </div>
    </DynamicBg>
</template>



<script setup>
import FormInput from './FormInput.vue';


</script>



<style lang="sass" scoped>
    .bg-blacko

        background-repeat: no-repeat
        background-position: center
        background-size: cover
        @apply pb-[800px] relative
    .text
        @apply absolute top-[200px] left-28 w-[35%]
</style>