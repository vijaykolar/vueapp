<template>
    <div id="app">

        <header>

            <NavBar/>
        </header>
        <main>
            <Banner/>
            <Features/>

        </main>
    </div>
</template>

<script>
import NavBar from './components/NavBar';
import Banner from './components/Banner';
import Features from './components/Features';

export default {
    name: 'app',
    components: {
        NavBar,
        Banner,
        Features
    }
}
</script>

<style>
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

    }

    .title--white {
        color: #fff;
    }

    .title--lg {
        font-size: 72px;
    }

    .info {
        font-size: 18px;
        font-family: "Lato-Regular",sans-serif;

    }

    .info--white {
        color: #fff;
    }

</style>
