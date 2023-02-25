<script>
  import "./scss/style.css";
  import Nav from "./lib/Nav.svelte";
  import Hero from "./lib/Hero.svelte";
  import Second from "./lib/Second.svelte";
  import Third from "./lib/Third.svelte";
  import Fourth from "./lib/Fourth.svelte";
  import Fifth from "./lib/Fifth.svelte";

  import Footer from "./lib/Footer.svelte";
</script>

<Nav class="nav fixed" />
<Hero class="section section__1 row" />
<Second class="section section__2 column" />
<Third class="section section__3 row" />
<Fourth class="section section__4 row" />
<Fifth class="section section__5 row" />

<Footer class="section section__3 " />

<style lang="scss">
</style>
