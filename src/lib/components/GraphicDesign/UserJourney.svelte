<div class="wrapper">
  <div>
    <p class="red-underline">set goals and values</p>
    <img
      class="arrow-right-down-curved"
      alt="An arrow pointing from left upper to right lower"
      width="120px"
      height="120x"
      src="/ui/partials/graphic-design/red-arrow-right-down-curved.svg"
    />
  </div>
  <div class="bottom">
    <p>exploration & moodboards</p>
  </div>
  <div>
    <p>sketches</p>
  </div>
  <div class="bottom">
    <p>transforming the chosen one</p>
  </div>
  <div>
    <p>working on colors, type...</p>
  </div>
  <div class="bottom">
    <p>finalizing your brand!</p>
  </div>
</div>

<style lang="scss">
  img {
    font-size: 0;
  }
  // base is 1024px and more
  .wrapper {
    margin-top: 4rem;
    display: flex;
    flex-direction: row;
    place-content: center;
    div {
      position: relative;
      height: 180px;
      width: 120px;
      margin: 0 1rem 0 1rem;
      p {
        position: absolute;
        margin: 0;
      }
      img {
        position: absolute;
        right: -110px;
        bottom: 60px;
      }
    }
    .bottom {
      p {
        bottom: 0;
      }
    }
  }
  .red-underline {
    text-decoration: underline;
    text-decoration-color: red;
    text-decoration-thickness: 2px;
  }
</style>
