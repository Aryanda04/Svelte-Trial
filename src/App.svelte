<script>
  import Header from "./components/Header.svelte";
  import List from "./components/List.svelte";
</script>

<div class="container"><Header /><List /></div>

<style>
  .container {
    display: block;
    margin: 0 auto;
    width: 500px;
    background: #009579;
  }
  :global(.conteiner *) {
    font-family: sans-serif;
  }
</style>
