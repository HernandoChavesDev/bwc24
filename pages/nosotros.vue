<template>
    <div>
        <AboutSection1 />
        <AboutSection2 />
        <AboutSection5 />
        <ServiciosSection5 />
        <AboutServiciosHor />
    </div>
</template>

<script setup>
    useHead({
        title: 'Quienes somos | BWC',
        meta:[
            {
                name:'description',
                content:'Conoce algo de nosotros | BWC'
            }
        ],
        bodyAttrs: {
            class: "navbar-dark scheme-magenta"
        },
    })
</script>