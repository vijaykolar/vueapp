<template>
    <section class="section section-features">
        <div class="container">

        </div>
    </section>
</template>


<script>
export default {
    name: 'Features'
}
</script>

<style scoped>
    .section-features {
        background-color: #fff;
        position: relative;
    }

    .section-features:before {
        position: absolute;
        height: 600px;
        width: 100%;
        content: '';
        top: -350px;
        transform: skewY(-5deg);
        /* z-index: -1; */
        background-color: #fff;

    }
</style>
