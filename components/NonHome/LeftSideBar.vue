<template>
    <div class="bg flex flex-col gap-4 border-gray0 border-r pt-24">
        <NonHomeSideItem v-for="el in array"> {{ el }} </NonHomeSideItem>
        <Button btn="secondary">Contacto con la escuela</Button>
    </div>
</template>


<script setup>
defineProps({
array: Array,
})
</script>


<style lang="sass" scoped>

</style>