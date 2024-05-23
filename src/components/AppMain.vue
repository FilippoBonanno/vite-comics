<script>
export default {
  data() {
    return {
      cards: [
        {
          img: "../assets/img/dc-logo.png",
          name: "digital comics",
        },
        {
          img: "../assets/img/dc-logo.png",
          name: "dc merchandise",
        },
        {
          img: "../assets/img/dc-logo.png",
          name: "subscription",
        },
        {
          img: "../assets/img/dc-logo.png",
          name: "comic shop locator",
        },
        {
          img: "../assets/img/dc-logo.png",
          name: "dc power visa",
        },
      ],

    }
  }
}
</script>

<template>
  <main>
    <div class="mainContainer container d-flex align-items-center">
      <p>--Content goes here <----</p>
    </div>
    <div class="cardsContainer d-flex align-items-center">
      <ul class="nav nav-underline container d-flex align-items-center justify-content-between">
        <li v-for="card in cards" class="nav-item d-flex align-items-center">
          <img :src="card.img">
          <a class="nav-link link-light" aria-current="page" href="#">{{ card.name }}</a>

        </li>
      </ul>

    </div>
  </main>
</template>

<style>
.cardsContainer {
  background-color: #0282F9;
  height: 8rem;
}

a{
  color: white;
}
</style>