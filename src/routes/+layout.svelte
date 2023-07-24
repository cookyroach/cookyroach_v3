<script>
  import Header from "../lib/header.svelte";
  import Footer from "../lib/footer.svelte";
</script>

<Header />
<slot />
<Footer />

<style>
  :global(html) {
    scroll-behavior: smooth;
  }
  :global(body) {
    margin: 0;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-family: "Gaegu", sans-serif;
    line-height: 1.1;
    font-size: 1.75rem;
  }

  :global(h1) {
    font-size: 3rem;
    margin: 1rem 0;
  }

  :global(h2) {
    font-size: 2.5rem;
    margin: 0.5rem 0;
    font-weight: normal;
  }

  :global(h3) {
    font-size: 2.5rem;
    margin: 0.5rem 0;
  }

  :global(p) {
    font-size: 1.75rem;
  }

  :global(a, button) {
    font-size: inherit;
    font-family: inherit;
  }

  :global(a:not(.button)) {
    color: #e26788;
    text-decoration: none;
    border-bottom: 3px dotted;
  }

  :global(.button) {
    background: #ffd97b;
    border: 2.5px solid black;
    border-radius: 24px 5px 31px 4px/4px 18px 4px 18px;
    font-weight: bold;
    padding: 0.25rem 0.5rem;
    text-decoration: none;
    color: inherit;
    display: inline-block;
  }
</style>
