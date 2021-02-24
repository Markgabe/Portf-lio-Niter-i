<script>
  import { Link } from "svelte-routing";
</script>

<nav>
  <Link class="link" to="/">
    <img src="../../assets/img/logo-4.png" alt="Prefeitura de Niterói" />
  </Link>
  <div>
    <Link class="link" to="/desk">Pesquisa Desk</Link>
    <Link class="link" to="/personas">Personas</Link>
  </div>
</nav>

<style>
  nav {
    position: fixed;
    background: linear-gradient(to bottom, #fff, #fffa, #fff0);
    display: flex;
    flex-direction: row;
    height: 6rem;
    width: 100%;
    align-items: center;
  }

  div {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    margin-left: auto;
    padding: 30px;
    width: 30%;
  }

  img {
    height: 120px;
    padding: 20px;
    margin-left: 20px;
  }

  nav :global(a) {
    color: #333;
    font-size: 1.4rem;

    transition: transform 0.2s;
  }

  nav :global(a):hover {
    text-decoration: none;

    transform: scale(1.1);
  }
</style>
