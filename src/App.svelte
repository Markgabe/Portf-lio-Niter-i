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
    <Route path="/" component={Home} />
    <Route path="/form" component={Questionario} />
    <Route path="/desk" component={Desk} />
    <Route path="/personas" component={Personas} />
    <Route path="/analise" component={Analise} />
    <Route path="/brainstorm" component={Brainstorm} />
  </Layout>
</Router>
