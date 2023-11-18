<script lang="ts">
  const boxes: ShowcaseBox[] = [
    {
      description: "a sneaker brand",
      href: "/graphic-design/hermes",
      title: "hermes",
      year: 2021,
    },
    {
      description: "a tree discovery website",
      href: "/graphic-design/stromy-trebonska",
      title: "stromy třeboňska",
      year: 2023,
    },
    {
      description: "a sneaker brand",
      href: "/graphic-design/hermes",
      title: "hermes",
      year: 2021,
    },
    {
      description: "a tree discovery website",
      href: "/graphic-design/stromy-trebonska",
      title: "stromy třeboňska",
      year: 2023,
    },
    {
      description: "a sneaker brand",
      href: "/graphic-design/hermes",
      title: "hermes",
      year: 2021,
    },
  ];
</script>

<h1>Graphic Design</h1>

<div class="wrapper">
  {#each boxes as box}
    <a href={box.href}>
      <div class="box">
        <div class="title">{box.title}</div>
        <div class="description">{box.description}</div>
        <div class="year-tag">{box.year}</div>
        <img
          class="arrow-up-right"
          alt="An arrow pointing to to the top right corner of each box"
          width="40px"
          height="40px"
          src="/assets/arrow-up-right.svg"
        />
      </div>
    </a>
  {/each}
</div>

<style lang="scss">
  .wrapper {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    place-content: center;
    column-gap: 4rem;
    row-gap: 2rem;
    margin-top: 4rem;
    line-height: 1.2;
  }
  @media screen and (min-width: 1280px) {
    .wrapper {
      column-gap: 8rem;
    }
  }
  .box {
    position: relative;
    border-style: solid;
    text-align: start;
    border-width: 2px;
    height: 18rem;
    width: 18rem;
  }
  @media screen and (max-width: 640px) {
    .box {
      height: 12rem;
      width: 12rem;
    }
  }
  .title {
    position: absolute;
    left: 1rem;
    top: 0.5rem;
    width: 9rem;
    font-size: 1.5rem;
  }
  .description {
    position: absolute;
    bottom: 0.5rem;
    left: 1rem;
  }
  .year-tag {
    position: absolute;
    right: -3rem;
    bottom: 0.5rem;
    width: 3rem;
    line-height: 1.5rem;
    border-top-right-radius: 1rem;
    border-bottom-right-radius: 1rem;
    // TODO: move colors to variables
    text-align: center;
    color: #f3f3f3;
    background-color: black;
  }
  .arrow-up-right {
    position: absolute;
    right: 0;
    top: 0;
  }
  a {
    color: inherit;
    text-decoration: none;
  }
</style>
