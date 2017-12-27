<template>
   <section class="section HighLigth">

       <div class="container">
           <div class="highligth-wrapper clearfix">

               <!--Left Content-->
                <div class="col-4" >
                    <div class="highlight-info" v-for='info in chatInfo' >
                        <h3>{{info.msg}}</h3>
                        <p>{{info.content}} </p>
                    </div>

                    <img src="../assets/chat-bubble.png" alt="chat-bubble">
                </div>

                <!-- Phone -->
                <div class="col-4">

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
                        <h3>{{info.msg}}</h3>
                        <p>{{info.content}} </p>
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
    }
    .phone-container {
        position: relative;
        overflow: hidden;
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
