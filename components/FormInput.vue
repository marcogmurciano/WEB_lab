<template>
    <form action="" class="bg flex gap-6">
        <input type="text" placeholder="Placejolder">
        <Button btn="primary" :icon="true" > Búsqueda </Button>
    </form>
</template>


<script setup>

</script>


<style lang="sass" scoped>
    
    input
        @apply rounded w-full
    input::placeholder
        @apply text-gray2 pl-2
        font-family: 'Poppins'
        font-weight: normal
        line-height: 20px
        font-size: 12px
</style>