<template>
    <div class="reviews-1-wrapper">
        <Swiper
            :modules="[SwiperAutoplay, SwiperEffectCreative]"
            :slides-per-view="1"
            :loop="true"
            :autoplay="{
                delay: 8000,
                disableOnInteraction: true
            }"
            :breakpoints="{
                600:{ slidesPerView:2 },
                920:{ slidesPerView:3 },
            }"
        >
            <SwiperSlide>
                <CommonSingleTestimonial>
                    <template v-slot:testimonio >Increíble servicio de diseño web. La atención personalizada y la calidad del trabajo superaron mis expectativas. ¡Gracias por hacer mi visión realidad!</template>
                    <template v-slot:img >
                        <img src="~assets/images/ramiro-tibacucha.jpg" alt="review-avatar" />
                    </template>
                    <template v-slot:nombre>Ramiro Tibacucha L.</template>
                    <template v-slot:cargo>Director encargado </template>
                </CommonSingleTestimonial>
            </SwiperSlide>
            <SwiperSlide>
                <CommonSingleTestimonial>
                    <template v-slot:testimonio >El equipo de BWC entendió mis necesidades y entregó un sitio web impresionante en tiempo récord. ¡Altamente recomendado!</template>
                    <template v-slot:img >
                        <img src="~assets/images/laura-manrique.jpg" alt="review-avatar" />
                    </template>
                    <template v-slot:nombre>Laura Manrique</template>
                    <template v-slot:cargo>Directora general </template>
                </CommonSingleTestimonial>
            </SwiperSlide>
            <SwiperSlide>
                <CommonSingleTestimonial>
                    <template v-slot:testimonio >La experiencia de trabajar con esta agencia fue genial. Cumplieron con mis expectativas y entregaron un sitio web de calidad.</template>
                    <template v-slot:img >
                        <img src="~assets/images/ramiro-suexcun.png" alt="review-avatar" />
                    </template>
                    <template v-slot:nombre>Ramiro Suezcun</template>
                    <template v-slot:cargo>Propietario </template>
                </CommonSingleTestimonial>
            </SwiperSlide>
            <SwiperSlide>
                <CommonSingleTestimonial>
                    <template v-slot:testimonio >Recomendaría a esta agencia a cualquiera que busque un diseño web profesional. Su equipo es altamente competente y siempre dispuesto a ayudar.</template>
                    <template v-slot:img >
                        <img src="~assets/images/jorge-contreras.png" alt="review-avatar" />
                    </template>
                    <template v-slot:nombre>Jorge Contreras</template>
                    <template v-slot:cargo>Gerente </template>
                </CommonSingleTestimonial>
            </SwiperSlide>
        </Swiper>
    </div>
</template>
