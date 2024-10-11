<script>

export default {
    data() {
        return {
            navList: [
                "characters",
                "comics",
                "movies",
                "tv",
                "games",
                "collectibles",
                "videos",
                "fans",
                "news",
                "shop"
            ]


        }
    }
}

</script>

<template>
    <header>
        <div class="headerContainer container d-flex justify-content-between align-items-center">
            <img src ="/public/img/dc-logo.png">
            <ul class="nav nav-underline">
                <li v-for="element in navList" class="nav-item">
                    <a class="nav-link " aria-current="page" href="#">{{element.toUpperCase()}}</a>
                    
                </li>
            </ul>
        </div>
    </header>
</template>

<style scoped></style>