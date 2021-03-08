<script>
  import { Router, Route } from "svelte-routing";
  import Layout from "./layout/Layout.svelte";
  import Questionario from "./pages/Questionario.svelte";
  import Home from "./pages/Home.svelte";
  import Personas from "./pages/Personas.svelte";
  import Desk from "./pages/Desk.svelte";
  import Analise from "./pages/Analise.svelte";
  import Brainstorm from "./pages/Brainstorm.svelte";
</script>

<Router>
  <Layout>
    <Route path="/"><Home /></Route>
    <Route path="/form"><Questionario /></Route>
    <Route path="/desk"><Desk /></Route>
    <Route path="/personas"><Personas /></Route>
    <Route path="/analise"><Analise /></Route>
    <Route path="/brainstorm"><Brainstorm /></Route>
  </Layout>
</Router>
