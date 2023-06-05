<template>
    <title>E/S/D/ Home</title>
    <div class="app">
        <Header class="fixed w-full z-50"></Header>
        <BannerHome></BannerHome>
        <div class="main relative w-full top-[-30px] z-40">
            <div class="body w-full flex flex-col gap-24">
                <CardBanner class="max-w-[1280px] m-auto w-full"></CardBanner>
                <div class="sec max-w-[1280px] m-auto">
                    <SectionHeader>Oferta educativa</SectionHeader>
                    <div class="mainsec">
                        <div class="line">
                            <CardOferta class="w-full" img="Card_offer1.png">Diseño Gráfico </CardOferta>
                            <CardOferta class="w-full" img="Card_offer2.png">Diseño de Producto </CardOferta>
                            <CardOferta class="w-full" img="Card_offer3.png">Diseño de Interiores </CardOferta>
                            <CardOferta class="w-full" img="Card_offer4.png">Diseño de Moda </CardOferta>
                        </div>
                        <div class="line ">
                            <CardOferta class="w-full" img="Card_offer5.png">Máster en diseño interactivo (MDI)</CardOferta>
                            <CardOferta class="w-full" img="Card_offer6.png">Máster en diseño de espacios comerciales (MDEC)
                            </CardOferta>
                        </div>
                    </div>
                </div>
                <div class="sec max-w-[1280px] m-auto">
                    <SectionHeader>Proyecto de alumnos</SectionHeader>
                    <div class="flex w-full gap-12">
                        <CardTFG class="w-[33%]" img="tfg1.png" autor="Carla Herrera" tfg="TFM"> Cuerpo en movimiento
                        </CardTFG>
                        <div class="mainsec w-full">
                            <div class="line h-[244px]">
                                <CardTFG class="w-[50%]" img="tfg2.png" autor="Valeria Torres" tfg="TFG"> Transmutando el
                                    espacio </CardTFG>
                                <CardTFG class="w-full" img="tfg.png" autor="Diego Paredes" tfg="TFG"> Recorridos urbanos:
                                    Diseño de señalética </CardTFG>
                            </div>
                            <div class="line h-[244px]">
                                <CardTFG class="w-full" img="tfg3.png" autor="Juan Morales" tfg="TFM"> Nuevas narrativas
                                    visuales </CardTFG>
                                <CardTFG class="w-[50%]" img="tfg4.png" autor="Isabel Castro" tfg="TFG"> Migraciones
                                    gráficas </CardTFG>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="bg-gray0 py-24">
                    <div class="sec max-w-[1280px] m-auto">
                        <SectionHeader>Actualidad</SectionHeader>
                        <div class="line">
                            <CardActualidad class="w-full" img="Actualidad3.png" hour="12:30" date="12/08/23"
                                name="Charla sistemas Constructivos Knauf"> El próximo 4 de mayo, jueves, tendrá lugar una
                                charla y demostración a cargo de la empresa Knauf, en el aula 0.7, en la que nos mostrarán
                                sus sistemas de tabiquería y falsos techos con placas de yeso laminado. Dada la limitación
                                de aforo la charla está dirigida preferentemente a los alumnos de interiores. La charla
                                comenzará a las 15:30 </CardActualidad>
                            <CardActualidad class="w-full" img="Actualidad2.png" hour="10:22" date="12/08/23"
                                name="Talleres en el jardín">Desde la Comisión de Convivencia de la ESD os invitamos a
                                colaborar con la asignatura de Proyecto de Jardín de interiores. En ella se está
                                construyendo un jardín comestible y se realizará una plantación de tintóreas además de
                                proyectar una isla de biodiversidad. Se realizarán varios talleres y sesiones, están
                                abiertos a toda la comunidad educativa con la intención de generar espacios comunes donde
                                interactuar. </CardActualidad>
                            <CardActualidad class="w-full" img="Actualidad1.png" hour="17:23" date="12/08/23"
                                name="Conferencia dibujando el silencio">
                                El próximo 9 de Mayo a las 12.30h en el Aula 0.7 contaremos con la presencia del artista
                                visual António Jorge Gonçalves que impartirá la conferencia DIBUJANDO EL SILENCIO.
                                En esta charla António traza un camino que cruza el Cómic, la Caricatura Política, la
                                Escenografía para Teatro, los Espectáculos de Dibujo en Vivo y los Proyectos Pedagógicos.
                                Esta conferencia es posible gracias a la Embajada de Portugal y a Mateo Feijóo.
                                Te esperamos!!
                            </CardActualidad>
                            <CardActualidad class="w-full" img="img3.png" hour="11:07" date="12/08/23"
                                name="Cómo proteger tu creatividad: valora tu diseño"> Benito Stkarcx Co-Ceo, socio fundador y Director del
                                Área Legal de PADIMA, Doctor en Derecho Mercantil y Profesor Honorifico de Derecho Mercantil
                                en la Universidad de Alicante, Magister Lucentinus en Propiedad Industrial e Intelectual
                                (Alicante) y Agente Oficial de la Propiedad Industrial acreditado ante la EUIPO, OEPM y OEP.
                            </CardActualidad>
                        </div>
                    </div>

                </div>
                <div class="sec max-w-[1280px] m-auto">
                    <SectionHeader>Empresas Colaboradoras</SectionHeader>
                    <div class="mainsec">
                        <div class="line justify-center">
                            <div class="logocont">
                                <img class="logo max-w-[130px]" src="/public/logo1.jpeg" alt="">
                            </div>
                            <div class="logocont">
                                <img class="logo max-w-[100px]" src="/public/logo2.jpeg" alt="">
                            </div>
                            <div class="logocont">
                                <img class="logo max-w-[60px]" src="/public/logo3.png" alt="">
                            </div>
                            <div class="logocont">
                                <img class="logo max-w-[120px]" src="/public/logo4.png" alt="">
                            </div>
                            <div class="logocont">
                                <img class="logo max-w-[100px]" src="/public/logo5.png" alt="">
                            </div>
                        </div>
                        <div class="line justify-center">

                            <div class="logocont">
                                <img class="logo max-w-[80px]" src="/public/logo6.png" alt="">
                            </div>
                            <div class="logocont">
                                <img class="logo max-w-[140px]" src="/public/logo7.png" alt="">
                            </div>
                            <div class="logocont">
                                <img class="logo max-w-[190px]" src="/public/logo11.png" alt="">
                            </div>
                            <div class="logocont">
                                <img class="logo max-w-[150px]" src="/public/logo8.jpeg" alt="">
                            </div>
                            <div class="logocont">
                                <img class="logo max-w-[130px]" src="/public/logo9.jpeg" alt="">
                            </div>
                        </div>

                    </div>
                </div>
                <div class="bg-gray0 py-24">
                    <div class="sec max-w-[1280px] m-auto">
                        <SectionHeader>Internacional</SectionHeader>
                        <AcordeonPics></AcordeonPics>
                    </div>

                </div>
            </div>
            <Footer></Footer>
        </div>
    </div>
</template>

<!-- 
    CHULETA COMPONENTES
<Button btn="primary" :icon="true" > Búsqueda </Button> 

                <Header></Header>

                <Footer></Footer>

                <AcordeonPics />

                <BannerHome />

                <FormInput />

                <CardBanner />

                <CardOferta img="sample_image.png"/>

                <CardTFG img="sample_image.png"/>

                <CardActualidad img="sample_image.png"/>

                <SectionHeader> el texto aqui </SectionHeader>

                <TextDropdown>esta sería toda la puta parrafada contenida por el texto dropdown mentienes chavalín?
                    soy un caracol peligroso, no juegues conmigo, tengo una granada escondida en al bolsa escrotal, y mi bolsa
                    ESCROTAL es muy elástica así que en cuanto te despistes puedo lanzarte la granada a la puta cara.
                </TextDropdown>

                <MyLink :icon="true" :alter="false">Esto sería un link sabes</MyLink>
                <MyLink :icon="true" :alter="true">Esto sería un link sabes</MyLink>

                <NonHomeLeftSideBar :array="sideArray" />
                const sideArray = [
                        'zsfd',
                        'azwesdfrgx',
                        'ewzfr',
                        'waezsfr',
                    ]

                <NonHomeCard img="/sample_image.png" tit="iván huelves" text="diseñador gráfico"></NonHomeCard>

                <NonHomeLinkCard tit="titulon"></NonHomeLinkCard>

                <NonHomeBanner></NonHomeBanner>

                <TableCelda num="37" :has-num="true" bold="" color="gray4"> blip blop</TableCelda>
   
                <TableFull></TableFull>

-->

<script setup>

</script>

<style lang="sass" scoped>

   
.sec
    @apply flex flex-col gap-20 w-full

.mainsec
    @apply flex flex-col gap-12

.line
    @apply flex gap-12
.logocont
    @apply flex items-center w-[150px] justify-center 
    filter: grayscale(1)

</style>




