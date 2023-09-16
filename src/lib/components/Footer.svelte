<script>
  const currentYear = new Date().getFullYear();
  import "@fortawesome/fontawesome-free/css/all.min.css";
</script>

<div class="wrapper">
  <hr />
  <footer>
    <p>Copyright {currentYear} © Alexandra Chloe Winkel</p>
    <div>
      <a
        class="icon-link"
        aria-label="Linkedin"
        href="https://www.linkedin.com/in/alexandra-chloe-winkel-ab5040180/"
        rel="noreferrer"
        target="_blank"
      >
        <i class="fa-brands fa-linkedin" />
      </a>
      <a
        class="icon-link"
        aria-label="Behance"
        href="https://www.behance.net/winkelchloe"
        rel="noreferrer"
        target="_blank"
      >
        <i class="fa-brands fa-behance" />
      </a>
    </div>
  </footer>
</div>

<style lang="scss">
  .icon-link {
    color: inherit;
  }
  p {
    margin: 0;
  }
  .wrapper {
    margin-bottom: 0.5rem;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
    hr {
      width: 100%;
      opacity: 0.8;
      margin-bottom: 1rem;
      color: getColor(green);
    }
    footer {
      display: flex;
      place-content: center;
      text-align: center;
      align-items: center;
      column-gap: 1rem;
      div {
        display: inherit;
        column-gap: inherit;
      }
    }
  }
  @media screen and (max-width: 640px) {
    footer {
      flex-direction: column;
      align-items: center;
      row-gap: 0.6rem;
    }
  }
</style>
