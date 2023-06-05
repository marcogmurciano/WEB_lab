<template>
    <div class="bg grid grid-cols-4 gap-9 w-full">
        <div class="col">
            <TableCelda :num="el.num" :has-num="(el.num === 0) ? false : true" :bold="el.bold" :color="el.color"
                v-for="el in array1"> {{ el.txt }} </TableCelda>
        </div>
        <div class="col">
            <TableCelda :num="el.num" :has-num="(el.num === 0) ? false : true" :bold="el.bold" :color="el.color"
                v-for="el in array2"> {{ el.txt }} </TableCelda>
        </div>
        <div class="col">
            <TableCelda :num="el.num" :has-num="(el.num === 0) ? false : true" :bold="el.bold" :color="el.color"
                v-for="el in array3"> {{ el.txt }} </TableCelda>
        </div>
        <div class="col">
            <TableCelda :num="el.num" :has-num="(el.num === 0) ? false : true" :bold="el.bold" :color="el.color"
                v-for="el in array4"> {{ el.txt }} </TableCelda>
        </div>
    </div>
</template>


<script setup>
const array1 = [
    {
        txt: 'Curso 1ª',
        color: 'blacko',
        num: 0,
        bold: 'bold'
    },
    {
        txt: 'Fundamentos del diseño. Análisis',
        color: 'white',
        num: 6,
        bold: ''
    },
    {
        txt: 'Fundamentos de diseño. Ideación',
        color: 'white',
        num: 6,
        bold: ''
    },
    {
        txt: 'Dibujo. Representación',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Dibujo. Comunicación',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Volumen',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Sistemas de representación',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Tecnología Digital',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Color',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Fundamentos científicos para el diseño',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Ecodiseño',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Teoría e historia del arte',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Tecnología digital gráfica',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Teoría de la imagen y de la comunicación',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Total ECTS',
        color: 'blacko',
        num: 60,
        bold: ''
    },
]

const array2 = [
    {
        txt: 'Curso 2ª',
        color: 'blacko',
        num: 0,
        bold: 'bold'
    },
    {
        txt: 'Fotografía y audiovisuales',
        color: 'white',
        num: 6,
        bold: ''
    },
    {
        txt: 'Técnicas de expresión y comunicación',
        color: 'white',
        num: 6,
        bold: ''
    },
    {
        txt: 'Teoría e historia del diseño',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Tipografía impresa',
        color: 'white',
        num: 4,
        bold: ''
    },
    {
        txt: 'Tipografía digital',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Fundamentos de estampación e impresión',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Sistemas de reproducción e impresión',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Gráfica Interactiva. Edición',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Gráfica Interactiva. Usabilidad',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Iniciación al Diseño Audiovisual',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Proyectos de diseño gráfico',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Proyectos de diseño gráfico. Desarrollos',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Técnicas de expresión gráfica', 
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Optativas',
        color: 'gray4',
        num: 4,
        bold: ''
    },
    {
        txt: 'Total ECTS',
        color: 'blacko',
        num: 60,
        bold: ''
    },
]
const array3 = [
    {
        txt: 'Curso 3ª',
        color: 'blacko',
        num: 0,
        bold: 'bold'
    },
    {
        txt: 'Estética',
        color: 'white',
        num: 6,
        bold: ''
    },
    {
        txt: 'Organización Empresarial',
        color: 'white',
        num: 6,
        bold: ''
    },
    {
        txt: 'Técnica fotográfica',
        color: 'gray0',
        num: 6,
        bold: ''
    },
    {
        txt: 'Expresión fotográfica',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Gráfica multimedia. Producción',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Gráfica multimedia. Programación',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Diseño audiovisual. Postproducción',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Diseño audiovisual. Proyectos',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Historia del diseño gráfico',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Proyectos de diseño gráfico. Implementación',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Proyectos interdisciplinares de Diseño Gráfico',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Diseño editorial',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Ilustración y comunicación visual',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Ilustración. Lenguajes y procesos',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Optativas',
        color: 'gray4',
        num: 4,
        bold: ''
    },
    {
        txt: 'Total ECTS',
        color: 'blacko',
        num: 60,
        bold: ''
    },
]
const array4 = [
    {
        txt: 'Curso 4ª',
        color: 'blacko',
        num: 0,
        bold: 'bold'
    },
    {
        txt: 'Producción para artes gráficas',
        color: 'gray0',
        num: 6,
        bold: ''
    },
    {
        txt: 'Proyectos experimentales de Diseño Gráfico',
        color: 'gray0',
        num: 6,
        bold: ''
    },
    {
        txt: 'Protección del diseño',
        color: 'gray0',
        num: 4,
        bold: ''
    },
    {
        txt: 'Optativas',
        color: 'gray4',
        num: 24,
        bold: ''
    },
    {
        txt: 'Prácticas',
        color: 'white',
        num: 12,
        bold: ''
    },
    {
        txt: 'Trabajo Fin de Grado',
        color: 'white',
        num: 12,
        bold: ''
    },
    {
        txt: 'Total ECTS',
        color: 'blacko',
        num: 60,
        bold: ''
    },
]

</script>


<style lang="sass" scoped>
    .col
        @apply flex flex-col
</style>