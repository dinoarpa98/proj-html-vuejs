<template>
    <main>
        <div class="container">

            <div class="row-1">
                <div class="col-1">
                    <p>
                        HAC TELLUS, FELIS RISUS AT mattis mattis. Eget cuismod
                        semper eget tortor, donec amet, blandit. Tristique facilisi faucibus
                        elementum feugiat in nam in feugiat. Ipsum odio etiam duis
                        facilisis amet vulputate.
                    </p>

                    <h1 class="title-m">
                        FOOD IS OUR COMMON
                        GROUND, A UNIVERSAL
                        EXPERIENCE.
                    </h1>

                    <p>
                        Tristique tempus condimentum diam donec. Condimentum
                        ullamcorper sit elementum hendrerit mi nulla in consequat, ut.
                        Metus, nullam scelerisque netus viverra dui.
                    </p>

                    <img class="signature" src="../../assets/img/signature-200x172.jpg" alt="">
                </div>

                <div class="col-6 relative">
                    <img src="../../assets/img/info22x.jpg" alt="">
                    <p class="price">CALIFORNIA ROLLS - $22</p>
                </div>
            </div>

            <div class="row-2">
                <div class="card">
                    <img src="../../assets/sushi-1.png" alt="">

                    <span class="border">
                        _______
                    </span>

                    <h1 class="card-title">THE BEST TABLE TABLE IN TOWN</h1>

                    <p class="card-text">Sed aenean egestas ut aliquam turpis mauris,
                        molestie. Vitae tellus tempor sem id tempus
                        neque, tellus turpis turpis. Morbi tortor id
                        gravida aliquet.</p>

                    <button class="btn"> 
                        EXPLORE THE MENU
                    </button>
                </div>

                <div class="card">
                    <img src="../../assets/sushi-2.png" alt="">

                    <span class="border">
                        _______
                    </span>

                    <h1 class="card-title">PERFECT FOR GROUPS</h1>

                    <p class="card-text">Quam eu proin sit massa condimentum.
                        Volutpat non pulvinar aliquet nunc. Orci
                        elementum in aliquet a gravida vivamus
                        aliquam turpis vitae.</p>

                    <button class="btn">
                        EXPLORE THE MENU
                    </button>
                </div>

                <div class="card">
                    <img src="../../assets/sushi-3.png" alt="">

                    <span class="border">
                        _______
                    </span>

                    <h1 class="card-title">FRESH PRODUCE EVERYDAY</h1>

                    <p class="card-text">Hendrerit amet, volutpat leo non, commodo
                        maecenas scelerisque tincidunt. Morbi
                        vulputate morbi purus quisque sit sagittis orci
                        elementum gravida.</p>

                    <button class="btn">
                        EXPLORE THE MENU
                    </button>
                </div>
            </div>
        </div>
    </main>

</template>

<script>
    export default {
        name: 'FoodDescr',

    }
</script>

<style scoped lang="scss">
    .container {
        padding: 20px;
    }

    .row-1 {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .col-1 {
        width: 20%;
        padding: 10px;
        margin-left: 50px;
    }

    .title-m {
        margin: 10px 0;
    }

    .col-6 {
        width: 40%;
        display: flex;
        justify-content: center;
    }

    .col-6 img {
        width: 50%;
        display: flex;
    }

    .relative {
        position: relative;
    }

    .price {
        position: absolute;
        left: 35%;
        bottom: 5px;
        color: white;
        padding: 5px;
    }

    // p2

    .row-2 {
        display: flex;
        padding: 30px;
        margin-top: 30px;
    }

    .card {
        width: 33%;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .card img {
        width: 20%;

    }

    .border {
        color: grey;
        margin: 3px 0px;
    }

    .card-title {
        font-size: 1.1em;
        padding: 10px;
    }

   .btn{
        margin-top: 20px;
        background-color:black;
        color: white;
        border: 1px solid white;
        padding: 10px 20px;
    }
</style>