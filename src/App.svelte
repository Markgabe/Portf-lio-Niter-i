<script>
  import { Router, Route } from "svelte-routing";
  import Layout from "./layout/Layout.svelte";
  import Pesquisa from "./pages/Pesquisa.svelte";
  import Home from "./pages/Home.svelte";
  import Personas from "./pages/Personas.svelte";
  import Desk from "./pages/Desk.svelte";
  import Analise from "./pages/Analise.svelte";
</script>

<Router>
  <Layout>
    <Route path="/" component={Home} />
    <Route path="/pesquisa" component={Pesquisa} />
    <Route path="/desk" component={Desk} />
    <Route path="/personas" component={Personas} />
    <Route path="/analise" component={Analise} />
  </Layout>
</Router>
