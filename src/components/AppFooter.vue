<script>
export default {
  data() {
    return {
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

  <footer>
    <div class="containerFooter container d-flex">

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

    <div class="footerSocial container d-flex justify-content-between align-items-center">
      <button type="button" class="btn btn-secondary btn-lg">Large button</button>
      <ul class="nav nav-underline">
        <li class="nav-item">
          <a class="nav-link " href="#">LOGO</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">LOGO</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">LOGO</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">LOGO</a>
        </li>
      </ul>
    </div>
  </footer>

</template>

<style>
footer {
  background-image: url(../assets/img/footer-bg.jpg);
}

.containerFooter>div {
  padding: 2rem;


}

.footerSocial {
  background-color: lightgrey;
}
</style>