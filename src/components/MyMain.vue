<!-- HTML -->
<template>
            <div class="container">
                <ul>
                    <li v-for="(link, i) in comic" :key="i">
                        <img :src="link.thumb" alt="">
                        <div id="series">{{link.series}}</div>
                    </li>
                </ul>
            </div>
</template>

<!-- javascript -->

<script>
    export default {
        name: 'MyMain',

        props: {
            comic: Array,
        }
    }

</script>

<!-- CSS -->

<style scoped>
    .container {
        background-color: rgb(61, 61, 61);
        color: white;
        padding: 50px;
    }
    ul {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }
    li {
        display: inline-block;
        margin: 15px;
    }
    img {

        width: 150px;
        height: 150px;

    }
    #series {
        font-size: small;
        max-width: 150px;
    }
    
</style>