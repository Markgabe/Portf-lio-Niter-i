<script>
	import { Router, Route } from "svelte-routing";
	import Menu from "./components/Menu.svelte";
	import Pesquisa from './pages/Pesquisa.svelte';
	import Container from "./layout/container.svelte";
	/*
	import Contact from "./pages/contact.svelte";
	import About from "./pages/about.svelte";
	import Home from "./pages/home.svelte";*/
</script>

<Router>
	<Menu />
  <Container>
	  <Route path='/pesquisa' component={Pesquisa} />
    <!-- 
			<Route path="/" component={Home} />
			<Route path="/contact" component={Contact} />
			<Route path="/about" component={About} />
		-->
  </Container>
</Router>
