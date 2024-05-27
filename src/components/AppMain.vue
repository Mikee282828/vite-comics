<script>
import ComicsList from "./ComicsList.vue";
export default {
    components:{
        ComicsList
    },
    data() {
        return {
            sections: [
                {
                    name: "digital",
                    url: "buy-comics-digital-comics.png",
                    body: "DIGITAL"
                },
                {
                    name: "merchandise",
                    url: "buy-comics-merchandise.png",
                    body: "MERCHANDISE"
                },
                {
                    name: "subscriptions",
                    url: "buy-comics-subscriptions.png",
                    body: "SUBSCRIPTIONS"
                },
                {
                    name: "locator",
                    url: "buy-comics-shop-locator.png",
                    body: "LOCATOR"
                },
                {
                    name: "visa",
                    url: "buy-dc-power-visa.svg",
                    body: "VISA"
                },
            ],
        }
    },
    methods: {
        getImage(path) {
            let risultato = new URL(`../assets/vue-dc-comics-1/img/${path}`, import.meta.url);
            return risultato.href
        }
    }
}
</script>

<template>
    <div class="myBlackBkg">
        <div class="container">
            <ComicsList></ComicsList>
        </div>
    </div>

    <div class="myAzzureBkg">
        <div class="container">
            <div class="row myWhite py-5 px-3 justify-content-center">
                <div class="col align-self-center" v-for="buy in sections">
                    <img :src="getImage(buy.url)" :alt="buy.name">
                    {{ buy.body }}
                </div>
            </div>
        </div>
    </div>

</template>

<style scoped>
h4 {
    color: white;
}

.myBlackBkg {
    background-color: #222;
}

.myAzzureBkg {
    background-color: rgb(56, 128, 241);
}

[alt] {
    height: 2.5rem;
    padding-right: .5rem;
}

.myWhite {
    color: white;
}

.col {
    font-size: .8rem;
}
</style>