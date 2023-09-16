<script lang="ts">
  import Footer from "$lib/components/Footer.svelte";
  import "../app.scss";
</script>

<svelte:head>
  <title>Chloe Winkel</title>
</svelte:head>

<div class="wrapper">
  <p>Header component here</p>
  <main>
    <slot />
  </main>
</div>

<Footer />

<style lang="scss">
  .wrapper {
    margin-left: auto;
    margin-right: auto;
    max-width: 72rem;
    padding-left: 1rem;
    padding-right: 1rem;
  }
</style>
