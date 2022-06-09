<template>
    <div class="container">
        <span>
            <button>
                SIGN-UP NOW
            </button>
        </span>

        <ul>
            <li>FOLLOW US</li>
            <li><img src="../assets/img/footer-facebook.png" alt=""></li>
            <li><img src="../assets/img/footer-twitter.png" alt=""></li>
            <li><img src="../assets/img/footer-youtube.png" alt=""></li>
            <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
            <li><img src="../assets/img/footer-periscope.png" alt=""></li>


        </ul>





    </div>
    
</template>

<script>
    export default {
        name: 'MySecondoFooter',

    }



</script>

<style scoped>
    .container {
        background-color: rgb(80, 80, 80);
        display:flex;
        justify-content: space-around;
        align-items: center;
        
    }
    ul {
        display:flex;
        margin: 15px;
        align-items: center;
    }
    li {
        
        display: inline-block;
        list-style: none;
        color: blue;
        margin: 15px;
    }

    button {
        background-color: rgb(80, 80, 80);
        border: 3px solid aquamarine;
        padding: 15px;
        color: white;
    }


</style>