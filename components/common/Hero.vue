<template>
    <section class="page-hero-section ">
        <div class="page-hero-section-overlay bg--02 bg--scroll">
            <div class="container">
                <div class="row d-flex align-items-center mt-4">
                    <!-- TEXT BLOCK -->
                    <div class="col-md-5">
                        <div class="txt-block left-column wow fadeInRight">
                            <!-- Section ID -->
                            <span class="section-id"> 
                                <slot name="subtitulo" ></slot>
                            </span>
                            <!-- Title -->
                            <h2 class="s-56 w-700">
                                <slot name="titulo" ></slot>
                            </h2>
                                    
                            <!-- Text -->
                            <p class="p-lg w-400">
                                <slot name="parrafo"></slot>
                            </p>
                            <CommonButtons link="contacto" >Contáctanos</CommonButtons>
                        </div>
                    </div>
                    <!-- END TEXT BLOCK -->
                    <!-- IMAGE BLOCK -->
                    <div class="col-md-7">
                        <div class="img-block right-column wow fadeInLeft">
                            <slot name="imgHero" ></slot>
                        </div>
                    </div>
                </div>
                <!-- End row -->
            </div>
            <!-- End container -->
        </div>
        <!-- End Page Hero Section Overlay -->
        <!-- WAVE SHAPE BOTTOM -->
        <div class="wave-shape-bottom">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 170"><path fill-opacity="1" d="M0,160L120,160C240,160,480,160,720,138.7C960,117,1200,75,1320,53.3L1440,32L1440,320L1320,320C1200,320,960,320,720,320C480,320,240,320,120,320L0,320Z"></path></svg>
        </div>
    </section>
</template>
