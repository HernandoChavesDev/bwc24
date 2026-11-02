<script setup>
    const date = new Date();
    const anio = date.getFullYear();
</script>
<template>
    <footer id="footer-3" class="pt-100 footer ft-3-ntr">
        <div class="container">
            <hr />
            <!-- FOOTER DIVIDER LINE -->
            <!-- BOTTOM FOOTER -->
            <div class="bottom-footer">
                <div class="row row-cols-1 row-cols-md-2 d-flex align-items-center">
                    <!-- FOOTER COPYRIGHT -->
                    <div class="col">
                        <div class="footer-copyright">
                            <p class="p-sm">&copy; {{ anio }} BWC. <span>Todos los derechos reservados</span></p>
                        </div>
                    </div>
                    <!-- FOOTER SOCIALS -->
                    <div class="col">
                        <div class="d-flex justify-content-end ">
                            <p class="p-sm">Desarrollo por Hernando J. Chaves </p>
                        </div>
                    </div>
                </div>
                <!-- End row -->
            </div>
            <!-- END BOTTOM FOOTER -->
        </div>
        <!-- End container -->
        <FooterGoToTop />
    </footer>
</template>
