<!-- HTML -->
<template>
    <div class="container">
        
                <ul>
                    <li v-for="(link, i) in links" :key="i">
                        <a :href="link.url"><img :src="link.img"><span>{{link.text}}</span></a>
                    </li>
                </ul>
        

    </div>
    
</template>

<!-- javascript -->

<script>
    export default {
        name: 'MySecondMain',

    data(){
        return {
            links: [
                {
                    text: "DIGIATAL COMICS",
                    url: "#",
                    img: require("../assets/img/buy-comics-digital-comics.png")
                    
                }, 
                {
                    text: "DR MERCHANDISE",
                    url: "#",
                    img: require("../assets/img/buy-comics-merchandise.png")
                },
                {
                    text: "SUBSCRIPTIONS",
                    url: "#",
                    img: require("../assets/img/buy-comics-subscriptions.png")
                },
                {
                    text: "COMIC SHOP LOCATOR",
                    url: "#",
                    img: require("../assets/img/buy-comics-shop-locator.png")
                }, 
                {
                    text: "DS POWER VISA",
                    url: "#",
                    img: require("../assets/img/buy-dc-power-visa.svg")
                }
                
            ]
      }
  }




    }

</script>

<!-- CSS -->

<style scoped>
    div {
        background-color: rgb(0, 204, 204);
        color: white;
        height: 150px;
    }
    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    li {
        display: inline-block;
        padding-left: 15px;
        padding-right: 15px;
        height: 100%;

        
    }
    a {
        text-decoration: none;
        color: white;
        display: flex;
        align-items: center;
        
    }

    img {
        width: 50px;
        height: 65px;
    }
    
</style>