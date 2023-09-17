<script lang="ts">
  import Footer from "$lib/components/Footer.svelte";
  import "../app.scss";
</script>

<svelte:head>
  <title>Chloe Winkel</title>
</svelte:head>

<div class="wrapper">
  <main>
    <slot />
  </main>
</div>

<Footer />

<style lang="scss">
  .wrapper {
    display: flex;
    flex-direction: column;
    text-align: center;
    place-content: center;
    margin-left: auto;
    margin-right: auto;
    max-width: 72rem;
  }
  main {
    width: 100%;
  }
</style>
