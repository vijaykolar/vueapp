<template>

    <section class="section testimonial">
        <div class="container">
            <div class="text-center">
                <h3 class="title--lg title">What people say</h3>
            </div>

            <div class="testimonial-slider-wrapper clearfix">
                <div class="row">

                    <ul class="testimonial-slider ">
                        <li class="testimonial-slider__list ">
                            <div class="col-4">

                                <div class="testimonial-content">
                                    <p class="info--gray info">Lorem ipsum dolor sit amet, onsectetur adipisicing elit,Lorem ipsum dolor sit amet, onsectetur adipisicing elit, </p>

                                    <a href="javascript:void(0)" class="link">booking.com</a>
                            
                                </div>
                            </div>
                        </li>
                        <li class="testimonial-slider__list ">
                            <div class="col-4">

                                <div class="testimonial-content">
                                    <p class="info--gray info">Lorem ipsum dolor sit amet, onsectetur adipisicing elit,Lorem ipsum dolor sit amet, onsectetur adipisicing elit, </p>

                                    <a href="javascript:void(0)" class="link">booking.com</a>
                            
                                </div>
                            </div>
                        </li>
                        <li class="testimonial-slider__list ">
                            <div class="col-4">

                                <div class="testimonial-content">
                                    <p class="info--gray info">Lorem ipsum dolor sit amet, onsectetur adipisicing elit,Lorem ipsum dolor sit amet, onsectetur adipisicing elit, </p>

                                    <a href="javascript:void(0)" class="link">booking.com</a>
                            
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>

        </div>
    </section>



</template>



<script>
export default {
  name: "WhatPeopleSay",

  data() {
    return {
    //   title: "Simple, safe & beautiful."
    };
  }
};
</script>

<style>

    .testimonial-content {
        border: 1px solid #e5e5e5;
        padding: 30px;
        position: relative;

        
    }

    .testimonial-content::after {
        position: absolute;
        height: 15px;
        width: 15px;
        border: 1px solid #e5e5e5;
        background-color: #fff;
        bottom: -9px;
        transform: rotate(-45deg);
        left: 10px;
        content: '';
    }

    .testimonial-content .link {
        margin-top: 15px;
    }

    .link {
        text-transform: capitalize;
        color: #e52d35;
        font-family: "Lato-Regular",sans-serif;
        font-weight: 500;
    }

</style>
