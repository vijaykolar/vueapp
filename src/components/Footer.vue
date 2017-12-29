<template >

    <footer class="footer">
        <div class="container">
            <div class="footer-wrapper">
                <ul class="footer-menu">
                    <li class="footer-menu__list" v-for='link in linkItem'>
                        <a class="footer-menu__link" href="javascript:void(0)">{{link}}</a>
                    </li>
                </ul>
            </div>
        </div>
    </footer>

</template>

<script>
export default {

    name: 'Footer',
    data() {
        return {
            linkItem: ['about','faq','support','blog','Download']
        }
    }

}
</script>

<style scoped>

    .footer {
        border-top: 1px solid #e5e5e5;
        /* margin-to; */
    }

    .footer-menu__list {
        display: inline-block;
    }
    .footer-menu__link {
        color: #363636;
        font-family: 'Lato-Regular',sans-serif;
        font-size: 16px;
        font-weight: 400;
        line-height: 28px;
        text-transform: uppercase;
        padding: 30px 15px;
    }

</style>
