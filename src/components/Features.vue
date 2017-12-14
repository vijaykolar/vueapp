<template>
    <section class="section section-features">
        <div class="container">
            <div class="features-wrapper ">
                <div class="clearfix chat-list">
                    <div class="chat-img-wrapper col-6">
                        <img src="../assets/chat.png" :alt="alt"/>
                    </div>

                    <div class="chat-message-info col-6">

                        <h1 class="title title--lg title--black">{{message}}</h1>
                        <p class="info info--gray"> {{info}}</p>
                    </div>
                </div>

                <div class="clearfix chat-list">
                    <div class="chat-message-info padding col-6">

                        <h1 class="title title--lg title--black">{{message2}}</h1>
                        <p class="info info--gray"> {{info}}</p>
                    </div>
                    <div class="chat-img-wrapper col-6">
                        <img src="../assets/chat-2.png" :alt="alt"/>
                    </div>

                    
                </div>
               
               
               
            </div>
        </div>
    </section>
</template>


<script>
export default {
    name: 'Features',

    data() {
        return {

            
            alt: "Chat Message",
            message: "Easy Messaging",
            message2: "Keep in touch",
            info: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'

        }
    }
   
}

// new Vue({
//     name: 'Features',

// })
</script>

<style scoped>
    .section-features {
        background-color: #fff;
        position: relative;
        padding-top: 100px;
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

    .padding .info{
        padding-right: 100px;
    }

    .features-wrapper {
        position: relative;
    }
    .chat-message-info .info {
         
        margin-top: 30px;
        
    }
     .chat-message-info {
         
        margin-top: 150px;
        
    }

    .chat-list {
        margin-top: 100px;
    }
    .chat-list:first-child {
        margin-top: 0px;
    }

    /* .chat-messge-info-content {
        padding-left: 25px;
    } */
</style>
