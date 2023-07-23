<script>
  import Footer from "../lib/footer.svelte";
</script>

<header>cookyroach</header>
<main>
  <div class="panel" style="background: #ffeaef;">
    <div class="container">
      <h1>Hi! I'm a comic creator & illustrator</h1>
      <img src="img/roachy.png" width="175" alt="Roachy" />
    </div>
  </div>
  <h2 style="margin-bottom: -1rem;">comics</h2>
  <div class="panel" style="background: #ffeaef;">
    <div class="container">
      <h3>Pet Rocky</h3>
    </div>
    <img class="cover" src="img/thumbnail2_larger.jpg" alt="" />
    <div class="container">
      <p>90% cute, 10% dark</p>
      <div class="button-container">
        <a class="button" href="https://tapas.io/series/Pet-Rocky">Tapas</a>
        <a
          class="button"
          href="https://www.webtoons.com/en/challenge/pet-rocky/list?title_no=530695"
        >
          Webtoons
        </a>
      </div>
    </div>
  </div>
  <div class="panel" style="background: #ffd0ee;">
    <div class="container">
      <h3>My sister's boss <br /> is too sweet</h3>
    </div>
    <img class="cover" src="img/lick2.jpg" alt="" />
    <div class="container">
      <p>too sweet to resist!</p>
      <div class="button-container">
        <a
          class="button"
          href="https://www.webtoons.com/en/challenge/my-sisters-boss-is-too-sweet/list?title_no=837245"
        >
          Read it on Webtoons
        </a>
      </div>
    </div>
  </div>
  <div class="panel" style="background: #fff6e5;">
    <div class="container">
      <h2>Support me</h2>
      <img width="150" src="img/coin.png" alt="" />
      <div class="button-container">
        <a
          class="button"
          href="https://www.redbubble.com/people/cookyroach/shop?asc=u"
          >Redbubble shop</a
        >
        <a class="button" href="https://ko-fi.com/cookyroach">Ko-Fi </a>
      </div>
    </div>
  </div>
</main>
<Footer />

<style>
  header {
    text-align: center;
    padding: 1rem;
    font-size: 2.5rem;
  }

  main {
    display: flex;
    flex-direction: column;
    gap: 2rem;
    padding: 0 1rem;
    align-items: stretch;
    text-align: center;
  }

  .panel {
    border: 2.5px solid black;
    border-radius: 24px 5px 31px 4px/4px 18px 4px 18px;
    text-align: center;
    overflow: hidden;
    display: flex;
    flex-direction: column;
  }

  .panel h2,
  .panel h3 {
    font-size: 2.5rem;
    font-weight: bold;
    margin: 0;
  }

  .panel p {
    margin: 0;
  }

  .panel .cover {
    border-top: 2.5px solid;
    border-bottom: 2.5px solid;
  }

  .container {
    max-width: 800px;
    margin: auto;
    padding: 1rem;
    display: flex;
    flex-direction: column;
    gap: 1rem;
    align-items: center;
  }

  .button-container {
    margin-top: 0.5rem;
  }

  img {
    max-width: 100%;
  }
</style>
