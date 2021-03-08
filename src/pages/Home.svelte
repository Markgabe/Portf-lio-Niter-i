<script>
  import Hero from "../components/home/Hero.svelte";
  import Metas from "./Metas.svelte";
  import { title } from "../store.js";

  title.set("Metas de Design");
</script>

<Hero />

<Metas />
