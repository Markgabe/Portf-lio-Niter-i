<script>
  import { Link } from "svelte-routing";
</script>

<nav>
  <Link to="/" id="logo">Portfólio</Link>
  <div>
    <Link to="/desk">Pesquisa Desk</Link>
    <Link to="/analise">Analise Competitiva</Link>
    <Link to="/brainstorm">Brainstorm</Link>
    <Link to="/form">Questionário</Link>
  </div>
</nav>

<style lang="scss">
  nav {
    background: #f8f9fabb;
    display: flex;
    flex-direction: row;
    height: 6rem;
    width: 100%;
    padding: 20px;
    align-items: center;
    position: fixed;
  }

  div {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    margin-left: auto;
    padding: 30px;
  }

  nav :global(a) {
    white-space: nowrap;
    color: #333;
    font-size: 1.2rem;
    padding: 0.7em;

    transition: transform 0.2s;

    &:hover {
      text-decoration: none;
      transform: scale(1.1);
    }

    &[aria-current="page"] {
      font-weight: bolder;
      pointer-events: none;
      &::before {
        content: "> ";
        top: 0;
      }
    }
  }
</style>
