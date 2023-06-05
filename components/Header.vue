<template>
    <div class="bg-blacko">
        <div class="top border-b border-black">
            <div class=" text-white flex justify-between items-center py-5 max-w-[1280px] mx-auto w-full">
                <NuxtLink to="/" class="left flex gap-4 items-center">
                    <div class="logos flex gap-2 items-center">
                        <img src="/CAM_logo.svg" alt="" class="w-[20px] h-[20px]">
                        <img src="/ESD_logo.svg" alt="" class="w-[20px] h-[20px]">
                    </div>
                    <div class="h4">Escuela superior de diseño Madrid</div>
                </NuxtLink>
                <div class="flex gap-6 items-center">
                    <nav class="nav flex gap-5 items-center">
                        <div class="cuerpo text-white hover" :alter="true" @click="displayHeader()">Escuela</div>
                        <div class="cuerpo text-white hover" :alter="true" @click="displayHeader()">Admision</div>
                        <div class="cuerpo text-white hover" :alter="true" @click="displayHeader()">Estudios</div>
                        <div class="cuerpo text-white hover" :alter="true" @click="displayHeader()">Internacional</div>
                        <div class="cuerpo text-white hover" :alter="true" @click="displayHeader()">Información</div>
                    </nav>
                    <div class="right">
                        <Button btn="tertiary" :icon="false"> Buscar</Button>
                    </div>
                </div>
            </div>
        </div>
        <div class="down bg-blacko text-white flex justify-between items-center py-8 max-w-[1280px] mx-auto w-full"
            v-if="displaycounter">
            <div class="col">
                <div class="tit cuerpo bold">Grados</div>
                <MyLink :alter="true" class="item cuerpo light">Acceso a grado</MyLink>
                <MyLink :alter="true" class="item cuerpo light" to="Estudios">Especialidad de Gráfico</MyLink>
                <MyLink :alter="true" class="item cuerpo light">Especialidad de Moda</MyLink>
                <MyLink :alter="true" class="item cuerpo light">Especialidad de Interiores</MyLink>
                <MyLink :alter="true" class="item cuerpo light">Especialidad de Producto</MyLink>
            </div>
            <div class="col">
                <div class="tit cuerpo bold">Másters</div>
                <MyLink :alter="true" class="item cuerpo light">Acceso a MDI</MyLink>
                <MyLink :alter="true" class="item cuerpo light">Acceso a MDEC</MyLink>
                <MyLink :alter="true" class="item cuerpo light">Máster en diseño interactivo (MDI)</MyLink>
                <MyLink :alter="true" class="item cuerpo light">Máster en diseño de espacios comerciales (MDEC)</MyLink>
                <MyLink :alter="true" class="item cuerpo light"></MyLink>
            </div>
            <div class="col">
                <div class="tit cuerpo bold">Más información</div>
                <MyLink :alter="true" class="item cuerpo light">Optativas</MyLink>
                <MyLink :alter="true" class="item cuerpo light">Guías de estudio</MyLink>
                <MyLink :alter="true" class="item cuerpo light">Planes docentes</MyLink>

            </div>
        </div>
    </div>
</template>


<script setup>

const displaycounter = ref(false)
const displayHeader = () => {
    displaycounter.value = !displaycounter.value
}
</script>


<style lang="sass" scoped>
    .hover:hover
        @apply border-white border rounded-lg
    .hover
        @apply border-blacko border py-4 px-2

    .col
        @apply flex flex-col gap-4


</style>