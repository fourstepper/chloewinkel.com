<script lang="ts">
  import Footer from "$lib/components/Footer.svelte";
  import "../app.scss";
</script>

<main class="wrapper">
  <slot />
</main>

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
