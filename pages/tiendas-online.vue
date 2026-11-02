<template>
    <div>
        <TiendaHero />
        <TiendaFeatures />
        <ServiciosSection4 />
        <ServiciosSection5 />
        <AboutServiciosHor />

    </div>
</template>

<script setup>
    useHead({
        title: 'Tiendas Online | BWC',
        meta:[
            {
                name:'description',
                content:'Diseño y desarrollo de tiendas online'
            }
        ],
        bodyAttrs: {
            class: "navbar-dark scheme-magenta"
        },
    })
</script>