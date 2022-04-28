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

                   <p>
                       Pellentesque vitae viverra risus,sagittis.
                       Venenatis ridiculus scelerisque nisi in urna nulla.
                       Sit tempor a et nisl,ac felis.
                   </p>
                </div>
                
                </div> 

            </div>

            <div class="right-header bg-header">
                <div class="list-menu">
                    <ul>
                        <li>Home</li>
                        <li>Culinary History</li>
                        <li>Our Team</li>
                        <li>Our Menu</li>
                        <li>Takeout</li>
                        <li>Bulletin</li>
                        <li>Reservations</li>
                    </ul>
                </div>
            </div>

        </div>
    </header>
</template>

<script>
    export default {
        name: 'HeaderComp',

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

   .text-container{
       display: flex;
       justify-content: center;
       align-items: center;
       height: 50%;
       width: 50%;
       padding: 10px;
   }

   .title-drop{
       font-size: 40px;
   }

    .img-logo {
        margin-top: 10px;
    }

    .right-header {
        width: 65%;
    }

    .list-menu {
        display: flex;
        margin-top: 10px;
        padding: 30px;
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

    // .bg-header{
    //     background-image: url('./assets/img/slider52x.jpg');
    // }
</style>