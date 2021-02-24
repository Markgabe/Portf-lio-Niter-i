<script>
  import Container from "./Container.svelte";
  import Navbar from "./navbar/Navbar.svelte";
</script>

<Navbar />
<Container>
  <slot />
</Container>
