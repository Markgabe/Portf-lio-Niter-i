<script>
  import Container from "./Container.svelte";
  import Navbar from "./navbar/Navbar.svelte";

  import { title } from "../store.js";
  let currentTitle;

  title.subscribe((newTitle) => {
    console.log(newTitle);
    currentTitle = newTitle;
  });
</script>

<Navbar />
<h1>{currentTitle}</h1>
<Container>
  <slot />
</Container>

<style>
  h1 {
    margin-top: 7rem;
    margin-left: 3.7rem;
    align-self: flex-start;
    font-size: 3.5em;
    letter-spacing: 5px;
  }
</style>
