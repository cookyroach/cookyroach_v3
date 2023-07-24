<main>
  <div class="panel" style="background: #ffeaef;">
    <h1>Styleguide</h1>
    <p style="margin-top:0;">a guide for colors, fonts & more</p>
  </div>
  <h2>roachy</h2>
  <div class="panel">
    <div class="row">
      <img src="img/roachy.png" width="125" alt="" />
      <img src="img/coin.png" width="125" alt="" />
    </div>
    <p>arms are optional</p>
  </div>
  <h2>colors</h2>
  <div class="panel" style="align-items: stretch;">
    <div class="color" style="background: #ffd97b;">cookie #ffd97b</div>
    <div class="color" style="background: #fff6e5;">cava #fff6e5</div>
    <div class="color" style="background: #ffeaef;">cotton candy #ffeaef</div>
    <div class="color" style="background: #ffd0ee;">sweets #ffd0ee</div>
    <div class="color" style="background: #e26788; color: white;">
      gum #e26788
    </div>
    <div class="color" style="background: black; color: white;">
      roach #000000
    </div>
  </div>

  <h2>typography</h2>
  <div class="panel">
    <h3 style="font-weight: normal">Gaegu Normal</h3>
    <h3>Gaegu Bold</h3>
  </div>
  <h2>elements</h2>
  <div class="panel">
    <button class="button">Button</button>
    <a href="#">link</a>
    <div class="panel"><p>Panel</p></div>
  </div>
</main>

<style>
  main {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    padding: 2rem;
    align-items: stretch;
    text-align: center;
    max-width: 500px;
    margin: auto;
  }

  main > h2 {
    margin-top: 1.5rem;
  }

  .panel p {
    margin: 0;
  }

  .row {
    display: flex;
    gap: 1rem;
    align-items: center;
  }

  .color {
    padding: 1rem 2rem;
    border-radius: 24px 5px 31px 4px/4px 18px 4px 18px;
  }

  .panel {
    border: 2.5px solid black;
    border-radius: 24px 5px 31px 4px/4px 18px 4px 18px;
    text-align: center;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 1.5rem;
    gap: 1.5rem;
    min-width: 150px;
  }
</style>
