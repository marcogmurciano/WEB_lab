<template>
    <title>Estudios/Gráfico</title>
    <div class="app  relative">
        <Header class="fixed w-full z-50"></Header>
        <NonHomeBanner> </NonHomeBanner>
        <div class="main flex max-w-[1280px] m-auto">
            <NonHomeLeftSideBar :array="sideArray" class="w-[25%] estiqui pr-6 h-auto top-2 items-start" />
            <div class="body flex flex-col gap-24 pt-24 w-full ml-6">
                <div class="cards gap-10 border-y border-gray0 w-full py-10">
                    <div class="line grid grid-cols-4 ">
                        <div class="card flex flex-col justify-center items-center">
                            <div class="mini bold">
                                Fecha Inicio
                            </div>
                            <div class="mini">
                                11/09/2023
                            </div>
                        </div>
                        <div class="card flex flex-col justify-center items-center">
                            <div class="mini bold">
                                Plazas Disponibles
                            </div>
                            <div class="mini">
                                50
                            </div>
                        </div>
                        <div class="card flex flex-col justify-center items-center">
                            <div class="mini bold">
                                Créditos
                            </div>
                            <div class="mini">
                                244 créditos
                            </div>
                        </div>
                        <div class="card flex flex-col justify-center items-center">
                            <div class="mini bold">
                                Requisitos de admisición
                            </div>
                            <div class="mini">
                                Especificados más abajo
                            </div>
                        </div>
                        <div class="card flex flex-col justify-center items-center">
                            <div class="mini bold">
                                Plazo de inscripción
                            </div>
                            <div class="mini">
                                Junio-Julio
                            </div>
                        </div>
                        <div class="card flex flex-col justify-center items-center">
                            <div class="mini bold">
                                Metodología
                            </div>
                            <div class="mini">
                                Presencial
                            </div>
                        </div>
                        <div class="card flex flex-col justify-center items-center">
                            <div class="mini bold">
                                Duración
                            </div>
                            <div class="mini">
                                4 años
                            </div>
                        </div>
                        <div class="card flex flex-col justify-center items-center">
                            <div class="mini bold">
                                Titulación
                            </div>
                            <div class="mini">
                                Grado
                            </div>
                        </div>
                    </div>

                </div>
                <div class="cuerpo bg-gray0 p-10">
                    Dentro del Título de Grado en en Enseñanzas Artísticas Superiores de Diseño, título oficial adaptado al
                    Espacio Europeo de Educación Superior, puedes obtener esta especialización en Diseño Gráfico.
                    El <span class="bold">diseñador gráfico</span> es un creador cuya actividad tiene por objeto la
                    utilización del lenguaje gráfico
                    para generar mensajes y comunicar contenidos de naturaleza diversa con diferentes medios y para los
                    distintos canales de comunicación.
                </div>
                <img src="/public/VideoIMG.png" alt="">
                <TextDropdown tit="¿A quién va dirigido?" typ="h2" class="pb-12 border-b border-gray0">El diseño gráfico es
                    una actividad interdisciplinar, dirigida a la resolución de problemas que combina sensibilidad visual
                    con habilidad y conocimiento principalmente en las áreas de comunicación, tecnología y negocios. Los
                    profesionales del diseño gráfico se especializan en la estructuración y la organización de la
                    información visual con vistas a optimizar la comunicación en sus múltiples manifestaciones y contextos
                    diversos.
                    <br> <br>
                    Debido al aumento veloz y masivo en el intercambio de información, la demanda de diseñadores gráficos es
                    mayor que nunca, particularmente a causa del desarrollo de nuevas tecnologías y de la necesidad de
                    comunicación de nuestro entorno social. Por ello formamos profesionales que generan soluciones visuales
                    a esas necesidades de comunicación mediante metodologías y procesos creativos y aplicando técnicas de
                    expresión gráfica y tecnologías computacionales, estableciendo con todo ello un código propio de
                    comunicación.
                    <br> <br>
                    Los ámbitos principales donde desarrolla su actividad son: identidad corporativa y visual, diseño
                    editorial, producción gráfica, diseño de envases y embalajes, dirección de arte en publicidad, diseño
                    audiovisual, grafismo en televisión, diseño multimedia, diseño de interacción, aplicaciones móviles,
                    diseño web, gráfica y comunicaciones aplicadas al espacio, investigación, docencia…
                    <br> <br>
                    Puedes acceder a estos estudios mediante prueba de acceso (si cuentas con un título de Bachillerato),
                    mediante acceso directo (si cuentas con un Título de Técnico Superior de Artes Plásticas y Diseño) o
                    mediante prueba de madurez (si no estás en ninguno de los dos casos anteriores).
                </TextDropdown>
                <div class="flex flex-col gap-9 pb-12 border-b border-gray0">
                    <div class="h2">
                        Plan de estudios
                    </div>
                    <TableFull />
                </div>
                <div class="flex flex-col gap-9">
                    <div class="h2">
                        Equipo Docente
                    </div>
                    <div class="gallery">
                        <div class="grid grid-cols-4">
                            <NonHomeCard img="portrait.png" tit="Iván huelves" text="Profesor de Diseño" />
                            <NonHomeCard img="portrait2.png" tit="Luisa Fernández" text="Diseñadora gráfica" />
                            <NonHomeCard img="portrait3.png" tit="Gabriel Martínez" text="Ilustrador" />
                            <NonHomeCard img="portrait4.png" tit="María Sánchez" text="Programadora visual" />
                            <NonHomeCard img="portrait5.png" tit="Javier Torres" text="Dibujante digital" />
                            <NonHomeCard img="portrait6.png" tit="Carolina Ramírez" text="Artista multimedia" />
                            <NonHomeCard img="portrait.png" tit="Pedro Herrera" text="Editor de imágenes" />
                            <NonHomeCard img="portrait2.png" tit="Ana Gómez" text="Animadora 3D" />
                            <NonHomeCard img="portrait3.png" tit="Roberto González" text="Diseñador de logotipos" />
                            <NonHomeCard img="portrait4.png" tit="Laura Vargas" text="Creativa visual" />
                            <NonHomeCard img="portrait5.png" tit="Andrés Mendoza" text="Retocador fotográfico" />
                            <NonHomeCard img="portrait6.png" tit="Isabel Castro" text="Diseñadora de interfaces" />
                            <NonHomeCard img="portrait.png" tit="Juan Morales" text="Arquitecto gráfico" />
                            <NonHomeCard img="portrait2.png" tit="Mónica López" text="Especialista en branding" />
                            <NonHomeCard img="portrait3.png" tit="Diego Paredes" text="Escultor digital" />
                            <NonHomeCard img="portrait4.png" tit="Valeria Torres" text="Diseñadora de empaques" />
                            <NonHomeCard img="portrait5.png" tit="Gustavo Ramírez" text="Director de arte" />
                            <NonHomeCard img="portrait6.png" tit="Carla Herrera" text="Técnica en preimpresión" />
                        </div>
                    </div>
                </div>
                <div class="flex flex-col gap-9">
                    <div class="h2">
                        Trabajos fin de grado
                    </div>
                    <div class="gallery">
                        <div class="grid grid-cols-4">
                            <NonHomeCard img="tfg.png" tit="Rediseño de Filmin" text="Sergio Pérez" />
                            <NonHomeCard img="tfg1.png" tit="Siempre Provocando. Diseño gráfico feminista"
                                text="Elena González" />
                            <NonHomeCard img="tfg2.png" tit="Locvi, Revista conceptual fotográfica"
                                text="Carlos Rodríguez" />
                            <NonHomeCard img="tfg3.png" tit="Reconstruyendo el paisaje urbano" text="María Fernández" />
                            <NonHomeCard img="tfg4.png" tit="Migraciones gráficas" text="Juan Martínez" />
                            <NonHomeCard img="img1.png" tit="Hacia lo abstracto: Explorando la forma y el color"
                                text="Laura Sánchez" />
                            <NonHomeCard img="img2.png" tit="Ecosistemas tipográficos" text="Alejandro Herrera" />
                            <NonHomeCard img="tfg.png" tit="Cuerpo en movimiento: Diseño de indumentaria deportiva"
                                text="Isabel García" />
                            <NonHomeCard img="img4.png" tit="Del pixel al lienzo: Arte digital en la pintura"
                                text="Andrés López" />
                            <NonHomeCard img="img5.png" tit="Revelando identidades: Fotografía documental"
                                text="Ana Navarro" />
                            <NonHomeCard img="img6.png" tit="Arte interactivo: Experiencias sensoriales"
                                text="Pablo Torres" />
                            <NonHomeCard img="img7.png" tit="Transmutando el espacio: Diseño de interiores"
                                text="Carolina Ruiz" />
                            <NonHomeCard img="tfg9.png" tit="Nuevas narrativas visuales" text="Roberto Vargas" />
                            <NonHomeCard img="tfg5.png" tit="El sonido de la imagen: Diseño sonoro en el cine"
                                text="Luisa Méndez" />
                            <NonHomeCard img="tfg6.png" tit="Recorridos urbanos: Diseño de señalética"
                                text="Daniel Castro" />
                            <NonHomeCard img="tfg7.png" tit="Reinterpretando la naturaleza: Ilustración botánica"
                                text="Laura Morales" />
                            <NonHomeCard img="tfg8.png" tit="Arquitectura sostenible: Integración con el entorno"
                                text="Carlos Gómez" />
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
            </div>
        </div>
        <Footer />
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
const sideArray = [
    'información general',
    '¿A quién va dirigido?',
    'Plan de Estudios',
    'Equipo Docente',
    'Trabajos fin de grado',
    'Empresas colaboradoras',
]
</script>


<style lang="sass" scoped>
    // *
    //     border: 1px solid tomato
    .estiqui
        position: sticky
    .gallery
        overflow-y: auto
        white-space: nowrap
        height: 180px
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