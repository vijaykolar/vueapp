<template>
    <nav class="navbar-menu navbar-fixed">
        <div class="container">
            <div class="brand-logo">
                <a href="javascript:void(0)">HeyU</a>
            </div>
            <ul class="navbar navbar-right"> 
                <li v-for="item in items" class="navbar__list"> 
                    <a href="javascript:void(0)" class="navbar__link">{{ item.list }}</a>
                </li>
            </ul>
        </div>
       
    </nav>
</template>

<script>
    export default {
        name: 'NavBar',
        data () {
        return {
            items: [
                {list: 'home'},
                {list: 'faq'},
                {list: 'support'},
                {list: 'blog'}
            ]
        }
    }

    
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    /* .navbar-menu {
        padding: 10px 0px;
    } */

    .navbar-fixed {
        position: fixed;
        top: 0px;
        left: 0px;
        width: 100%;
    }

    .brand-logo {
        float: left;
    }
    .brand-logo>a {
        padding: 10px 15px;
        font-weight: 800;
        color: #fff;
        color: #000;
        font-size: 30px;
    }

    .navbar-right {

        float: right;
        
    }

    .navbar__list {
        display: inline-block;
    }

    .navbar__link {
        font-size: 14px;
        color: #fff;
        color: #000;
        font-family: "Lato-Regular",sans-serif;
        padding: 23px 15px; 
        text-transform: uppercase;
        

    }

    


</style>
