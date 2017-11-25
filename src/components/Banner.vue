<template>

    <section class="section-banner">
        <div class="container">
            <div class="content content-banner clearfix">
                <div class="col-6">
                    <h1 class="title title--white title--lg">{{title}}</h1>
                    <p class="info info--white">{{info}}</p>
                    <Button/>
                </div>
                <div class="col-6">
                    <img src="../assets/banner-image.png" class="img-responsive banner-img" alt="Banner Image">
                </div>
            </div>
            
            
        </div>
    </section>

</template>

<script>
    export default {
        name: 'Banner',
        components: {
            Button
        },

        data() {
            return {
               title: 'Simple, safe & beautiful.',
               info: 'With HeyU, you will get fast, simple, secure messaging!',
            }
        }
    }
    import Button from './Button';
</script>



<style scoped>
    .section-banner {

        background: linear-gradient(#eb402c, #d90647);

    }

    .content-banner {
        padding-top: 150px;

    }

    .banner-img {
        position: relative;
        z-index: 2;
    }

    .section-banner .title {
        padding-top: 90px;
    }
    .section-banner .info {
        padding-top: 30px;
    }
    .section-banner .btn {
        margin-top: 30px;
    }
   
</style>

