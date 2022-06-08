<!-- HTML -->
<template>
    <div class="container">
        
                <ul>
                    <li v-for="(link, i) in links" :key="i">
                        <a :href="link.url">{{link.img}}{{link.text}}</a>
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
                    img: "../assets/img/buy-comics-digital-comics.png"
                    
                }, 
                {
                    text: "DR MERCHANDISE",
                    url: "#"
                },
                {
                    text: "SUBSCRIPTIONS",
                    url: "#"
                },
                {
                    text: "COMIC SHOP LOCATOR",
                    url: "#"
                }, 
                {
                    text: "DS POWER VISA",
                    url: "#"
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
        
    }
    
</style>