<script>
  import Footer from "$lib/components/Footer.svelte";
import "../app.scss";
</script>

<div class="wrapper">
  <main>
    <slot />
  </main>
	<Footer/>
</div>

<style lang="scss">
  .wrapper {
    gap: 1rem;
    margin-left: auto;
    margin-right: auto;
    max-width: 72rem;
    padding-left: 1rem;
    padding-right: 1rem;
  }
</style>
