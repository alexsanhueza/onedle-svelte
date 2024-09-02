<script>
  import Row from "./Row.svelte";
</script>

<div class="inner-game-container">
  <Row></Row>
  <Row></Row>
  <Row></Row>
  <Row></Row>
  <Row></Row>
</div>

<style>
  .inner-game-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    gap: 10px;
    height: 40%;
    width: 40%;
  }
</style>
