<script lang="ts">
  import Nav from "../components/Nav.svelte";
  import ShortcutLinks from "../components/ShortcutLinks.svelte";

  export let segment: string;
</script>

<style>
  main,
  header,
  footer {
    width: 100%;
    position: relative;
    max-width: 84rem;
    background-color: white;
    padding: 2rem;
    margin: 0 auto;
    box-sizing: border-box;
  }
  main {
    min-height: 80vh;
  }
  footer {
    height: 10rem;
    background-color: aliceblue;
    padding-bottom: 10rem;
  }
</style>

<header id="top">
  <ShortcutLinks />
  <Nav {segment} />
</header>

<main id="main-content">
  <slot />
</main>

<footer>
  <h3>Contact info</h3>
  <address>Name stuff</address>
  <a href="#top">Scroll to top</a>
</footer>
