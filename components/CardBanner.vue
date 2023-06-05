<template>
    <div class="bg flex px-20 py-9 justify-between">
        <div class="card">
            <ph-monitor :size="28" />
            <div class="h4">MODELO TEÓRICO-PRÁCTICA</div>
        </div>
        <div class="card">
            <ph-users-three :size="28" />
            <div class="h4">ENSEÑANZA PRESENCIAL</div>
        </div>
        <div class="card">
            <ph-wrench :size="28" />
            <div class="h4">ENSEÑANZA ESPECIALIZADA</div>
        </div>
    </div>
</template>


<script setup>
  import { PhMonitor, PhUsersThree, PhWrench} from "@phosphor-icons/vue";
</script>


<style lang="sass" scoped>
    .card
        @apply flex flex-col gap-4 items-center justify-center 
    img
        @apply w-6 h-6
    .bg
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)
        @apply bg-white

</style>