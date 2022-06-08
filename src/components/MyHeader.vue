<!-- HTML -->
<template>
    <header>
        <div class="container">
            <span>
                <img src="../assets/img/dc-logo.png" alt="" srcset="">
            </span>

            <span>

                <ul>
                    <li v-for="(link, i) in links" :key="i">
                        <a :href="link.url">{{link.text}}</a>
                    </li>
                </ul>

            </span>









        </div>
    </header>
</template>

<!-- javascript -->

<script>
    export default {
        name: 'MyHeader',

        data(){
        return {
            links: [
                {
                    text: "CHARACTERS",
                    url: "#"
                }, 
                {
                    text: "COMICS",
                    url: "#"
                },
                {
                    text: "MOVIES",
                    url: "#"
                },
                {
                    text: "TV",
                    url: "#"
                }, 
                {
                    text: "GAMES",
                    url: "#"
                },
                {
                    text: "COLLECTIBLES",
                    url: "#"
                }, 
                {
                    text: "VIDEO",
                    url: "#"
                },
                {
                    text: "FANS",
                    url: "#"
                }, 
                {
                    text: "NEWS",
                    url: "#"
                },
                {
                    text: "SHOP",
                    url: "#"
                }
            ]
      }
  }
    }

    


</script>

<!-- CSS -->

<style scoped>

    
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
        color: black;
        
    }

    a:hover {
        color:rgb(0, 204, 204);
        border-bottom: 5px solid;
        border-color: rgb(0, 204, 204);
        padding-bottom:25px;
    }

</style>