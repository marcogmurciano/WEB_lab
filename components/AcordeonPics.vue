<template>
    <div class="bg flex ">
        <div class="img_container">
            <div class="text">
                <div class="h4">
                    "Cuando eliges la Escuela Superior de Diseño de Madrid, te unes a una comunidad académica que ha
                    establecido sólidos vínculos con renombradas instituciones educativas de diseño alrededor del mundo, lo
                    que garantiza una formación de excelencia respaldada por una red global de prestigio."
                </div>
            </div>
            <img src="/img4.png" alt="">
        </div>
        <div class="img_container">
            <div class="text">
                <div class="h4">
                    "Nuestra escuela, la Escuela Superior de Diseño de Madrid, se enorgullece de su amplia red de alianzas
                    con instituciones líderes en educación en diseño a nivel internacional, asegurando una formación de
                    vanguardia y una conexión directa con las últimas tendencias del sector."
                </div>
            </div>
            <img src="/carr2.png" alt="">
        </div>
        <div class="img_container">
            <div class="text">
                <div class="h4">
                    "Confía en la Escuela Superior de Diseño de Madrid, donde establecemos colaboraciones estratégicas con
                    instituciones reconocidas a nivel global en la enseñanza del diseño, brindando a nuestros estudiantes
                    oportunidades únicas y una perspectiva global."
                </div>
            </div>
            <img src="/img1.png" alt="">
        </div>
        <div class="img_container">
            <div class="text">
                <div class="h4">
                    "En la Escuela Superior de Diseño de Madrid, compartimos lazos sólidos con instituciones de prestigio en
                    el campo de la enseñanza del diseño alrededor del mundo, garantizando una formación de calidad
                    internacional."
                </div>
            </div>
            <img src="/img2.png" alt="">
        </div>
    </div>
</template>


<script setup>

</script>


<style lang="sass" scoped>
    .bg
        width: 100%
        height: 400px
        justify-content: space-between
        align-items: center
        overflow: hidden
    img
        @apply h-full object-cover
    .img_container
        width: 25%
        position: relative
        overflow: hidden
        transition: width 0.3s ease
        @apply h-full
    .img_container:hover
        width: 36%
    .text
        position: absolute
        top: 0
        left: 0
        width: 100%
        height: 100%
        display: flex
        justify-content: center
        align-items: center
        background-color: rgba(0, 0, 0, 0.5)
        opacity: 0
        transition: opacity 0.3s ease
    .img_container:hover .text
        opacity: 1
    .h4
        color: white
        text-align: center
        padding: 1rem
</style>