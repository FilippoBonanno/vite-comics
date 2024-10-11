<script>
export default {
  data() {
    return {
      cards: [
        {
          img: "/public/img/buy-comics-digital-comics.png",
          name: "Digital Comics",
        },
        {
          img: "/public/img/buy-comics-merchandise.png",
          name: "DC Merchandise",
        },
        {
          img: "/public/img/buy-comics-shop-locator.png",
          name: "Subscription",
        },
        {
          img: "/public/img/buy-comics-subscriptions.png",
          name: "Comic Shop Locator",
        },
        {
          img: "/public/img/buy-dc-power-visa.svg",
          name: "DC Power Visa",
        },
      ],

      comics: [
        "Testo di prova1",
        "Testo di prova1",
        "Testo di prova1",
        "Testo di prova1",
        "Testo di prova1",
        "Testo di prova1",
        "Testo di prova1",
        "Testo di prova1",


      ],

      shop: [
        "Testo di prova2",
        "Testo di prova2",

      ],

      dc: [
        "Testo di prova3",
        "Testo di prova3",
        "Testo di prova3",
        "Testo di prova3",
        "Testo di prova3",
        "Testo di prova3",
        "Testo di prova3",
        "Testo di prova3",
        "Testo di prova3",
        "Testo di prova3",
        "Testo di prova3",

      ],

      sitis: [
        "Testo di prova4",
        "Testo di prova4",
        "Testo di prova4",
        "Testo di prova4",
        "Testo di prova4",

      ],

    }
  }
}
</script>

<template>
  <main>
    <div class="mainContainer container d-flex align-items-center">
      <p> --Content goes here <---- </p>
    </div>
    <div class="cardsContainer d-flex align-items-center">
      <ul class="nav nav-underline container d-flex align-items-center justify-content-between">
        <li v-for="card in cards" class="nav-item d-flex align-items-center">
          <img :src="card.img">
          <a class="nav-link link-light ms-3" aria-current="page" href="#">{{ card.name }}</a>

        </li>
      </ul>

    </div>

    <div class="containerFooter ">
      <div class="containerList container d-flex">
        <div>
          <h2>DC COMICS</h2>
          <ul>
            <li v-for="element in comics">{{ element }}</li>
          </ul>
          <h2>SHOP</h2>
          <ul>
            <li v-for="element in shop">{{ element }}</li>
          </ul>
        </div>

        <div>
          <h2>DC</h2>
          <ul>
            <li v-for="element in comics">{{ element }}</li>
          </ul>
        </div>

        <div>
          <h2>SITIS</h2>
          <ul>
            <li v-for="element in comics">{{ element }}</li>
          </ul>
        </div>
      </div>
    </div>
  </main>
</template>

<style>
.cardsContainer {
  background-color: #0282F9;
  height: 8rem;
}

a {
  color: white;
}

img {
  width: 4rem;
}

.containerFooter {
  background-image: url(../public/img/footer-bg.jpg);
}

.containerFooter>div {
  padding: 2rem;
}

.containerList {
  padding: 4rem;
}
</style>