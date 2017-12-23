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
                                <div class="test-user-menu__list">
                                    <img src="../assets/user.png" alt="John Doe">

                                    <div class="testimoonial-user">
                                       <h4 class="user-name">john doe</h4>
                                        <h6 class="user-position">ceo</h6>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li class="testimonial-slider__list ">
                            <div class="col-4">

                                <div class="testimonial-content">
                                    <p class="info--gray info">Lorem ipsum dolor sit amet, onsectetur adipisicing elit,Lorem ipsum dolor sit amet, onsectetur adipisicing elit, </p>

                                    <a href="javascript:void(0)" class="link">booking.com</a>
                            
                                </div>
                                <div class="test-user-menu__list">
                                    <img src="../assets/user.png" alt="John Doe">

                                    <div class="testimoonial-user">
                                       <h4 class="user-name">john doe</h4>
                                        <h6 class="user-position">ceo</h6>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li class="testimonial-slider__list ">
                            <div class="col-4">

                                <div class="testimonial-content">
                                    <p class="info--gray info">Lorem ipsum dolor sit amet, onsectetur adipisicing elit,Lorem ipsum dolor sit amet, onsectetur adipisicing elit, </p>

                                    <a href="javascript:void(0)" class="link">booking.com</a>
                            
                                </div>
                                <div class="test-user-menu__list">
                                    <img src="../assets/user.png" alt="John Doe">

                                    <div class="testimoonial-user">
                                        <h4 class="user-name">john doe</h4>
                                        <h6 class="user-position">ceo</h6>
                                    </div>
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

    .testimonial-slider-wrapper {
        margin-top: 70px;
    }

    .testimoonial-user {
        margin-left: 15px;
        /* margin-top: 30px; */
    }

    .user-name {
        color: #363636;
        font-family: "Lat-Regular", sans-serif;
        font-size: 18px;
        font-weight: 400;
        line-height: 28px;
        /* Text style for "John Doe" */
        letter-spacing: 1.08px;
        text-transform: capitalize;
    }

    .user-position {
        color: #667386;
        font-family: "Lat-Regular", sans-serif;
        /* font-family: Ubuntu; */
        font-size: 13px;
        font-weight: 400;
        /* line-height: 28px; */
        text-transform: uppercase;
        /* Text style for "CEO" */
        letter-spacing: 0.96px;
    }

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
        content: "";
    }

    .testimonial-content .link {
        margin-top: 15px;
    }

    .link {
        text-transform: capitalize;
        color: #e52d35;
        font-family: "Lato-Regular", sans-serif;
        font-weight: 500;
    }


    .test-user-menu__list {
        display: flex;
        align-items: center;
        margin-top: 30px;
    }

</style>
