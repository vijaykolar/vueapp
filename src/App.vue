<template>
    <div id="app">

        <header>

            <NavBar/>
        </header>
        <main>
            <Banner/>
            <Features/>
            <WhatPeopleSay/>
            
        </main>
    </div>
</template>

<script>
import NavBar from './components/NavBar';
import Banner from './components/Banner';
import Features from './components/Features';
import WhatPeopleSay from './components/WhatPeopleSay';

export default {
    name: 'app',
    components: {
        NavBar,
        Banner,
        Features,
        WhatPeopleSay

    }
}
</script>

<style>

    :root {

    }
    body,
    body * {
        margin: 0px;
        padding: 0px;
        font-family: "Lato-Regular",sans-serif;

    }
    /* main {
        margin-top: 62px;
    } */

    .container {
        padding: 0 15px;
        margin-left: auto;
        margin-right: auto;
    }

    ul {
        list-style-type: none;
    }

    a {
        display: inline-block;
        text-decoration: none;
    }

    @media(min-width: 768px) {
        .container {
            width: 750px;
        }
    }
    @media(min-width: 992px) {
        .container {
            width: 970px;
        }
    }
    @media(min-width: 1200px) {
        .container {
            width: 1170px;
        }
    }

    .col-6 {
        width: 50%;
        float: left;
    }
    .text-center {
        text-align: center;
    }

    .clearfix:after, .clearfix:before {
        content: " ";
        display: table;
    }

    .clearfix {
        overflow: auto;
    }
    .section {
        padding: 50px 0px;
    }

    .img-responsive {
        max-width: 100%;
        height: auto;
        display: block;
    }

     /* .content {
        width: 960px;
        margin: 0 auto;
    } */
    .title {
        font-weight: 700;
        font-family: "Lato-Regular",sans-serif;

    }

    .title--white {
        color: #fff;
        /* font-weight: 700; */
    }

    .title--black {
        color: #363636;
    }

    .title--lg {
        font-size: 72px;
    }

    .info {
        font-size: 18px;
        font-family: "Lato-Regular",sans-serif;
        line-height: 28px;

    }

    .info--white {
        color: #fff;
    }

    .info--gray {
        color: #808080;
    }

</style>
