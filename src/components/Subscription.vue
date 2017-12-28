<template>
    <section class="section subscription">
        <div class="container">
            <div class="text-center">
                <h2 class="title title--md">{{title}}</h2>
                <p class="info info--gray">{{info}}</p>

                <form class="subscribe-form" >
                        <div class="form-wrapper">

                            <input type="email" name="" required class="input-field" value="" placeholder='Your email adress'>
                            <button type="submit" class="btn btn--oval" name="button">subscribe</button>
                        </div>
                </form>
            </div>
        </div>
    </section>
</template>

<script>
export default {

    name: 'Subscription',
    data() {
        return {

            title: 'Subscribe to our newsletter',
            info: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua',
        }
    }


}
</script>

<style lang="css" scoped>
    .subscription {
        margin: 100px 0px;

    }
    .title--md {
        font-size: 60px;
    }
    .form-wrapper {
        width: 575px;
        margin: 50px auto 0px;
        position: relative;
    }




    .info--gray {
        margin-top: 15px;
    }

    .input-field {
        border-radius: 25px;
        background-color: #f8f8f8;
        border: 0px;
        padding: 18px 30px;
        display: inline-block;
        width: 100%;
        color: #808080;
    }

    .input-field:focus {
        outline: 0;
        box-shadow: 0;
    }

    .btn {
        box-shadow: 0 10px 30px rgba(223, 27, 61, 0.3);
        border-radius: 25px;
        background-color: #ffffff;
        background-image: linear-gradient(to top, #eb402c 0%, #d90647 100%);
        text-transform: capitalize;
        color: #fff;
        cursor: pointer;
        position: absolute;
        right: 0px;
        top: 0px;
        right: -24px;
        border: 0px;

    }

    .btn:focus,
    .btn:active {
        box-shadow: none;
        outline: none;
    }
</style>
