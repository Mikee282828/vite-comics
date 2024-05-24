<script>
export default{
    data(){
        return {
            headerItem:[
                "CHARACTERS",
                "COMICS",
                "MOVIES",
                "TV",
                "GAMES",
                "COLLECTIBLES",
                "VIDEOS",
                "FANS",
                "NEWS",
                "SHOP"
            ]
        }
    }
}
</script>

<template>

    <div class="container">
        <div class="row py-3 justify-content-between">
            <div class="col-1">
                <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="LOGO" class="myFixedSize">
            </div>
            <div class="col-9">
                <div class="d-flex h-100 align-items-center flex-nowrap myHeaderItem">
                    <div class="flex-fill" v-for="item in headerItem">{{item}}</div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.myHeaderItem {
    font-size: smaller;
    font-weight: bold;
}
.myFixedSize {
    height: 5rem;
}
</style>