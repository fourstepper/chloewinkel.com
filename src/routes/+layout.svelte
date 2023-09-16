<script>
  import Footer from "$lib/components/Footer.svelte";
import "../app.scss";
</script>

<main class="wrapper">
  <div>
    <slot />
  </div>
	<Footer/>
</main>

<style lang="scss">
div {
flex-grow: 1;
}
  .wrapper {
    display: flex;
		min-height: 100%;
    flex-direction: column;
    place-content: center;
    gap: 1rem;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: auto;
    max-width: 72rem;
    padding-left: 1rem;
    padding-right: 1rem;
  }
</style>
