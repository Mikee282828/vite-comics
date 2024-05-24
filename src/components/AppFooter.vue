<script>
</script>

<template>
    <div class="myComicBkg">

        <div class="container h-100">

            <div class="row justify-content-between flex-nowrap align-items-center h-100">
                <div class="col-5 myMenu ">
                    <div class="d-flex flex-column h-100 flex-wrap">
                        <div>
                            <h4>
                                DC COMICS
                            </h4>
                            <ul>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                            </ul>
                        </div>

                        <div>
                            <h4>
                                SHOP
                            </h4>
                            <ul>
                                <li>ciao</li>
                                <li>ciao</li>
                            </ul>
                        </div>

                        <div>
                            <h4>
                                DC
                            </h4>
                            <ul>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                            </ul>
                        </div>

                        <div>
                            <h4>
                                SITES
                            </h4>
                            <ul>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                                <li>ciao</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="col dc-bkg">
                    <div class="d-flex h-100 justify-content-end">
                        <img src="../assets/vue-dc-comics-1/img/dc-logo-bg.png" class="h-100">
                    </div>
                </div>

            </div>

        </div>

    </div>

    <div class="myFooterBkg">
        <div class="container">
            <div class="row py-3 justify-content-between">
                <button type="button" class="btn btn-outline-primary col-2">SIGN-UP NOW!</button>

                <div class="col-5">
                    <div class="d-flex h-100 align-items-center flex-nowrap myHeaderItem">
                        <div class="flex-fill">FOLLOW US</div>
                        <div class="flex-fill"></div>
                        <div class="flex-fill"></div>
                        <div class="flex-fill"></div>
                        <div class="flex-fill">GAMES</div>
                        <div class="flex-fill">COLLECTIBLES</div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<style scoped>
* {
    color: white;
}
.myComicBkg {
    background-image: url("../assets/vue-dc-comics-1/img/footer-bg.jpg");
    height: 25rem;
    position:relative;
    z-index:-1;
}
.myFooterBkg {
    background-color: #222;
}
.myMenu {
    height: 90%;
}
.dc-bkg{
    height: 130%; 
}

.myWhite {
    color: white;
}

li {
    font-size: 1rem;
    color: white;
}

ul {
  list-style: none;
  padding:0;
}
</style>