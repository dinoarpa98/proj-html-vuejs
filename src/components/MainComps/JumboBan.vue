<template>

    <div class="container">

        <div class="row">

            <div class="col-left">
                <img src="../../assets/img/slider32x.jpg" alt="plate">
            </div>

            <div class="col-right">
                 <div class="title-content">
                   <p>FINE DINING EXPERIENCE</p>
                  
                
                
                <h1 class="title-drop">
                    THE BEST TABLE IN TOWN
                </h1>

                <p>
                    endrerit amet, volutpat leo non, commodo
                    maecenas scelerisque tincidunt. Morbi
                    vulputate morbi purus quisque sit sagittis orci
                    elementum gravida.
                </p> 

                <button class="btn"> EXPLORE THE MENU </button>
                </div>
            </div>

        </div>

    </div>

</template>

<script>
    export default {
        name: 'JumboBan',

    }
</script>

<style scoped lang="scss">
    .container {
        background-color: black;
    }

    .row {
        display: flex;
    }

    .col-left {
        width: 50%;
    }

    .col-left img {
        width: 100%;
    }

    .col-right {
        color: white;
        width: 50%;
        padding: 50px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .title-content{
        width: 40%;
        padding: 20px;
    }

    .title-drop{
        margin: 20px 0px;
    }
    
    .btn{
        margin-top: 20px;
        background-color:black;
        color: white;
        border: 1px solid white;
        padding: 10px 20px;
    }
</style>