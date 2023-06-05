<template>
    <div class="bg-blacko py-[120px] text-white">
        <div class="cont flex justify-between max-w-[1280px] m-auto">
            <div class="flex items-center">
                <div class="left flex h-fit items-center">
                <img src="/ESD_logo.svg" alt="" class="w-10">
                <div class="mini uppercase max-w-[160px] pl-3">Escuela superior de diseño de madrid</div>
            </div>
            </div>
            <div class="right flex gap-32">
                <div class="col1 flex flex-col justify-between h-full">
                    <div class="h4 uppercase">
                        Síguenos
                    </div>
                    <ul class="flex flex-col">
                        <div class="item flex items-center">
                            <ph-facebook-logo :size="20" />
                            <MyLink :alter="true">Facebook</MyLink>
                        </div>
                        <div class="item flex items-center">
                            <ph-twitter-logo :size="20" />
                            <MyLink :alter="true">Twitter</MyLink>
                        </div>
                        <div class="item flex items-center">
                            <ph-instagram-logo :size="20" />
                            <MyLink :alter="true">Instagram</MyLink>
                        </div>
                        <div class="item flex items-center">
                            <ph-youtube-logo :size="20" />
                            <MyLink :alter="true">Youtube</MyLink>
                        </div>
                    </ul>
                </div>
                <div class="col2 flex flex-col justify-between h-full">
                    <div class="h4 uppercase">
                        legal y créditos
                    </div>
                    <ul class="flex flex-col">
                        <MyLink :alter="true">Política de privacidad</MyLink>
                        <MyLink :alter="true">Política de cookies</MyLink>
                        <MyLink :alter="true">Aviso Legal</MyLink>
                        <MyLink :alter="true">Créditos</MyLink>
                    </ul>
                </div>
                <div class="col3 flex flex-col">
                    <img src="/mapa_esd.jpg" alt="" class="h-[140px] w-[170px]">
                    <div class="mini max-w-[170px]">
                        Camino de Vinateros 10628030 Madrid Teléfono: 91 439 00 00 Fax: 91 437 96 39
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>


<script setup>
import { PhFacebookLogo, PhTwitterLogo, PhYoutubeLogo, PhInstagramLogo } from "@phosphor-icons/vue";
</script>


<style lang="sass" scoped>
    // *
        // border: 1px solid tomato
</style>