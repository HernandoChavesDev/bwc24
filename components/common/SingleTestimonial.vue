<template>
    <div class="review-1 bg--white-100 block-shadow r-08">
        <!-- Quote Icon -->
        <div class="review-ico ico-65"><span class="flaticon-quote"></span></div>
        <!-- Text -->
        <div class="review-txt">
            <!-- Text -->
            <p>
                <slot name="testimonio" />
            </p>
            <!-- Author -->
            <div class="author-data clearfix">
                <!-- Avatar -->
                <div class="review-avatar">
                    <slot name="img"></slot>
                </div>
                <!-- Data -->
                <div class="review-author">
                    <h6 class="s-18 w-700">
                        <slot name="nombre" />
                    </h6>
                    <p class="p-sm"><slot name="cargo" /> </p>
                </div>
            </div>
            <!-- End Author -->
        </div>
        <!-- End Text -->
    </div>
</template>