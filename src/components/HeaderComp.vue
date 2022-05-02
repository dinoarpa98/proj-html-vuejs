<template>
    <header>

        <div class="container">

            <div class="left-header bg-black">
                <div class="img-logo">
                    <img src="../assets/img/avada-restaurant-logo-new-2x.png" alt="avada logo">
                </div>


                <div class="text-container">
                    <div class="text-white headerText">
                        <h6>THE BEST TABLE IN TOWN</h6>

                        <p class="title-drop">
                            FINE DINING EXPERIENCE
                        </p>

                        <p class="par-width">
                            Pellentesque vitae viverra risus,sagittis.
                            Venenatis ridiculus scelerisque nisi in urna nulla.
                            Sit tempor a et nisl,ac felis.
                        </p>

                        <button class="btn">
                            EXPLORE THE MENU
                        </button>
                    </div>

                </div>

            </div>

            <div class="right-header bg-header">
                <div class="list-menu">
                    <ul>
                        <li class="list-unstyled" v-for="(link,index) in links" :key="index">
                            <a class="d-flex align-items-center text-decoration-none" :href="link.url">{{ link.title }}
                            </a>
                            
                        </li>
                      
                            <i class="fa-solid fa-cart-shopping"></i>
                    </ul>
                </div>
            </div>

        </div>
    </header>
</template>

<script>
    export default {
        name: 'HeaderComp',
        data: function () {
            return {
                activeLink: 1,
                links: [{
                        title: "Home",
                        url: "#",
                    },
                    {
                        title: "Culinary History",
                        url: "#",
                    },
                    {
                        title: "Our Teams",
                        url: "#",
                    },
                    {
                        title: "Takeout",
                        url: "#",
                    },
                    {
                        title: "Our Menu",
                        url: "#",
                    },
                    {
                        title: "Bulletin",
                        url: "#",
                    },
                    {
                        title: "Reservations",
                        url: "#",
                    },
                ],
            };
        },
    }
</script>


<style scoped lang="scss">
    //    colors-text

    .text-white {
        color: white;
    }



    .bg-black {
        background-color: rgb(0, 0, 0);
        width: 100%;
    }


    .left-header {
        width: 35%;
        display: flex;
        flex-direction: column;
        align-items: center;

    }

    .text-container {
        display: flex;
        align-items: center;
        height: 80%;
        padding: 40px;
        width: fit-content;
    }

    .title-drop {
        font-size: 70px;

    }

    .par-width {
        color: rgba(255, 255, 255, 0.836);
    }

    .btn {
        background-color: black;
        color: rgba(255, 255, 255, 0.849);
        padding: 10px;
        margin-top: 20px;
    }

    .img-logo {
        margin-top: 10px;
    }

    .right-header {
        width: 65%;
    }

    .list-menu {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 10px;
        padding: 30px;
    }

    .text-decoration-none {
        text-decoration: none;
        color: rgba(255, 255, 255, 0.486);
    }

    .list-menu li {
        list-style-type: none;
        display: inline;
        color: rgba(255, 255, 255, 0.89);
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        margin: 10px;
    }

    .container {
        display: flex;
        height: 100%;
    }

    .fa-cart-shopping{
        color: white;
    }

    // .bg-header{
    // //     background-image: url('./assets/img/slider52x.jpg');
    // }
</style>