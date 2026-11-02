<script setup>
    defineProps({
        link:{
            type:String,
            required:true
        }
    })
</script>
<template>
    <nuxt-link :to="link" class="btn r-04 btn--theme hover--theme"><slot /></nuxt-link>
</template>

