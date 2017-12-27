<template>
   <section class="section HighLigth">

       <div class="container">
           <div class="highligth-wrapper">

               <!--Left Content-->
                <div class="col-4 " >

                    <div class="highlight-info" v-for='info in chatInfo' >
                        <img src="../assets/chat-bubble.png" alt="chat-bubble">
                        <div>
                            <h3 class="highlight-title">{{info.msg}}</h3>
                            <p class="highlight-content">{{info.content}} </p>
                        </div>

                    </div>

                </div>

                <!-- Phone -->
                <div class="col-4 relative">

                    <div class="phone">
                        <div class="phone-container">

                            <img src="../assets/phone.png" alt="iPhone" class="img-responsive">
                            <img src="../assets/play.png" alt="Play Icon" class="play">
                        </div>
                    </div>

                </div>

                <!-- Right Content-->

                <div class="col-4">
                    <div class="highlight-info" v-for='info in msgInfo' >
                        <img src="../assets/chat-bubble.png" alt="chat-bubble">
                        <div>
                            <h3 class="highlight-title">{{info.msg}}</h3>
                            <p class="highlight-content">{{info.content}} </p>
                        </div>

                    </div>
                </div>

           </div>
       </div>
   </section>
</template>

<script>
    export default {
        name: 'HighLigth',
        data () {
        return {
            chatInfo: [
                {msg: 'Start conversation', content:'Lorem ipsum dolor sit amet, consectetur adipisicingsdf elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqu.' },
                {msg: 'make a call', content:'Lorem ipsum dolor sit amet, consectetur adipisicingsdf elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqu.' },
            ],

            msgInfo : [

                {msg: 'take a picture', content:'Lorem ipsum dolor sit amet, consectetur adipisicingsdf elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqu.' },
                {msg: 'send a video', content:'Lorem ipsum dolor sit amet, consectetur adipisicingsdf elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqu.' }
            ]
        }
    }


}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    .HighLigth {
        background:  linear-gradient(to top, #eb402c 0%, #d90647 100%);
        margin-top: 150px;
    }
    .highligth-wrapper {
        display: flex;
        align-items: center;
    }
    .highlight-info {
        display: flex;
        align-items: flex-start;
    }

    .highlight-info img {
        margin-right: 20px;
        margin-top: 15px;
    }
    .relative {
        position: relative;
    }
    .highlight-title {
        text-transform: capitalize;
        color: #fff;
        font-family: "Lato-Regular",sans-serif;
        font-size: 24px;
        font-weight: 600;
        letter-spacing: 1.44px;
        margin: 15px 0px;
    }


    .highlight-content {
        opacity: 0.6;
        color: #ffffff;
        font-family: Lato;
        font-size: 16px;
        font-weight: 400;
        line-height: 28px;
        /* Text style for "Lorem ipsu" */
        letter-spacing: 0.96px;
        margin-bottom: 50px;
    }

    .highlight-info:last-child {
        margin-bottom: 0px;
    }
    .phone-container {
        position: relative;
        overflow: hidden;
    }

    .phone {
        position: absolute;
        top: 0;
        left: 0;
        top: -50%;
        transform: translate(0%,-48%);
    }

    .phone-container::before {
        /* position: absolute;
        height: 100%;
        width: 100%;
        content: '';
        background-color: rgba(0,0,0,.6);
        top: 0px;
        left: 0px; */
    }
    .play {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
        cursor: pointer;
    }
</style>
