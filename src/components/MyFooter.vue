<!-- HTML -->
<template>
   <div class="container">
       <div>
            <ul>
                <h2>DC COMICS</h2>
                <li>Character</li>
                <li>Xomics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <ul>
                <h2>DC</h2>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
            </ul>
            <ul>
                <h2>DC</h2>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
            </ul>
        </div>
        <div class="dc">
        
        </div>

   </div>
    
</template>

<!-- javascript -->

<script>
    export default {
        name: 'MyMain',

    }

</script>

<!-- CSS -->

<style scoped>
    .container {
        background-image: url("../assets/img/footer-bg.jpg");
        background-size: 100%;
        color: white;
        display:flex;
        justify-content: space-between;
        height: 370px;
    }

    ul {
        display: inline-block;
        margin: 15px;
    }
    li {
        list-style: none;
        color: grey;
    }
    li:hover {
        color : white;
    }
    img {
        height:100%;
        width:auto;
    }
    .dc {
        background-image: url("../assets/img/dc-logo-bg.png");
        height: 100%;
        width: 50%;
        background-size: 100%;
        background-position: center;
    }

</style>