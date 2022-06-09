<!-- HTML -->
<template>
            <div class="container">
                <ul>
                    <li v-for="(link, i) in comic" :key="i">
                        <img :src="link.thumb" alt="">
                        <div>{{link.series}}</div>
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
        background-color: black;
        color: white;
        height: 150px;
    }
    ul {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }
    li {
        display: inline-block;
    }
    
</style>