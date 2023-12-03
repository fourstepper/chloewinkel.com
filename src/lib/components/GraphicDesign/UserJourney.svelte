<div class="wrapper">
  <div>
    <p class="red-underline">set goals and values</p>
    <img
      class="arrow-right-down-curved"
      alt="An arrow pointing from left upper to right lower"
      width="140px"
      height="140px"
      src="/ui/partials/graphic-design/red-arrow-right-down-curved.svg"
    />
  </div>
  <div class="bottom">
    <p>exploration & moodboards</p>
    <img
      class="steps-up"
      alt="An arrow pointing from left upper to right lower"
      width="140px"
      height="140px"
      src="/ui/partials/graphic-design/personal-progress-arrows-04.svg"
    />
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
  .wrapper {
    margin-top: 4rem;
    font-size: 1.2rem;
    display: flex;
    flex-direction: row;
    place-content: center;
    div {
      position: relative;
      margin: 1rem;
      height: 160px;
      width: 120px;
      p {
        position: absolute;
        margin: 0;
      }
      .arrow-right-down-curved {
        position: absolute;
        right: -110px;
        bottom: 40px;
      }
      .steps-up {
        position: absolute;
        right: -50px;
        bottom: 42px;
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
