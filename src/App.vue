<template>
    <div id="app">

        <NavBar/>
    </div>
</template>

<script>
import NavBar from './components/NavBar'

export default {
    name: 'app',
    components: {
        NavBar
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

</style>
