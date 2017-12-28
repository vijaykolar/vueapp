<template>
    <section class="downlaod section">
        <div class="container">
            <div class="text-center">
                <img src='../assets/h-logo.png' :alt=alt>
                <p class="info info--gray">{{info}}</p>
                <a href="#" class="app-icon" >

                    <img src='../assets/app.png' :alt=alt >
                </a>
            </div>
        </div>
    </section>
</template>

<script>
export default {

    name: 'Download',
    data() {
        return {

            alt: 'Hey Logo',
            info: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod',

        }
    }
}
</script>

<style scoped>
    .downlaod {
        border-top: 1px solid #e5e5e5;
    }
    .app-icon {
        margin-top: 50px;
        display: inline-block;
    }
</style>
