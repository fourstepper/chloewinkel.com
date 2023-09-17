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
    row-gap: 1rem;
  }
  .box {
    border-style: solid;
    border-width: 2px;
    display: relative;
    height: 18rem;
    width: 18rem;
  }
  @media screen and (max-width: 640px) {
    .box {
      height: 12rem;
      width: 12rem;
    }
  }
  a {
    color: inherit;
    text-decoration: none;
  }
</style>
