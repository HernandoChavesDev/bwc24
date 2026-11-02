<template>
    <section id="contacts-1" class="pb-50 inner-page-hero contacts-section division">
        <div class="container">
            <!-- SECTION TITLE -->
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-9">
                    <div class="section-title text-center mb-80">
                        <!-- Title -->
                        <h2 class="s-52 w-700">Dudas? Preguntas? Hablemos</h2>
                        <!-- Text -->
                        <p class="p-lg">Si deseas obtener más información sobre alguno de nuestros servicios, obtener una cotización o hablar con un experto, dejanos saber lo que estas buscando y nos comunicaremos contigo a la mayor brevedad posible.</p>
                    </div>
                </div>
            </div>
            <!-- CONTACT FORM -->
            <div class="row justify-content-center">
                <div class="col-md-11 col-lg-10 col-xl-8">
                    <div class="form-holder">
                        <form name="contactform" class="row contact-form">
                            <!-- Form Select -->
                            <div class="col-md-12 input-subject">
                                <p class="p-lg">Esta pregunta es sobre:</p>
                                <span>Elige un tema para que sepamos a quién enviar tu solicitud: </span>
                                <select class="form-select subject" aria-label="Default select example">
                                    <option selected>Esta pregunta es sobre...</option>
                                    <option>Identidad corporativa</option>
                                    <option>Diseño web</option>
                                    <option>Servicio técnico</option>
                                    <option>Otro</option>
                                </select>
                            </div>
                            <!-- Contact Form Input -->
                            <div class="col-md-12">
                                <p class="p-lg">Tu nombre:</p>
                                <input type="text" name="name" class="form-control name" placeholder="Escribe aquí tu nombre*" />
                            </div>
                            <div class="col-md-12">
                                <p class="p-lg">Tu correo:</p>
                                <input type="text" name="email" class="form-control email" placeholder="Escribe aquí tu correo*" />
                            </div>
                            <div class="col-md-12">
                                <p class="p-lg">Asunto:</p>
                                <textarea class="form-control message" name="message" rows="6" placeholder="Escribe aquí como podemos ayudarte..."></textarea>
                            </div>
                            <div class="col-md-12 mt-15 form-btn text-right">
                                <button type="submit" class="btn btn--theme hover--theme submit">Enviar</button>
                            </div>
                            <div class="col-lg-12 contact-form-msg">
                                <span class="loading"></span>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
            <!-- END CONTACT FORM -->
        </div>
        <!-- End container -->
    </section>
</template>
