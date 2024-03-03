<script lang="ts">
  import Greet from "./lib/Greet.svelte";
</script>

<main class="container">
  <h1>Welcome to Vegify!</h1>

  <div class="row">
    <a href="https://vegify.app" target="_blank">
      <img src="/vegify.svg" class="logo vegify" alt="Vegify Logo" />
    </a>
  </div>

  <p>What's your name?</p>

  <div class="row">
    <Greet />
  </div>
</main>

<style>
</style>
