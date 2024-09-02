<script>
  import Game from "../components/Game.svelte";
</script>

<div class="app-container">
  <div class="inner-app">
    <h1>Onedle</h1>
    <div class="game-container">
      <Game />
    </div>
  </div>
</div>

<style>
  :global(body) {
    margin: 0;
  }
  h1 {
    color: red;
    display: block;
    margin-top: 0;
  }

  .app-container {
    position: relative;
    background-color: antiquewhite;
    height: 100vh;
    margin: 0 !important;
  }
  .inner-app {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 60vw;
    margin: 0 auto;
    text-align: center;
    background-color: aliceblue;
    height: 100vh;
  }
  .game-container {
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid black;
    height: 70%;
    width: 70%;
  }
</style>
