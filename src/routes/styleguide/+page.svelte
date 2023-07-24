<main>
  <h1>styleguide</h1>
  <h2>roachy</h2>
  <div class="row">
    <img src="img/roachy.png" width="100" alt="" />
    <img src="img/coin.png" width="100" alt="" />
  </div>
  <h2>colors</h2>
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

  <h2>typography</h2>
  <h3 style="font-weight: normal">Gaegu Normal</h3>
  <h3>Gaegu Bold</h3>
  <h2>elements</h2>
  <button class="button">button</button>
  <a href="#">link</a>
  <div class="panel"><h3>panel</h3></div>
</main>

<style>
  main {
    display: flex;
    flex-direction: column;
    gap: 2rem;
    padding: 2rem;
    align-items: center;
    text-align: center;
    max-width: 500px;
    margin: auto;
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
    padding: 1rem;
    width: 100%;
    min-height: 200px;
    background: #ffeaef;
  }
</style>
