<script>
  import { Link } from "svelte-routing";
</script>

<nav>
  <Link to="/" id="logo">Portfólio</Link>
  <div>
    <Link to="/desk">Desk Research</Link>
    <Link to="/analise">Análise Competitiva</Link>
    <Link to="/brainstorm">Brainstorm</Link>
    <Link to="/form">Questionário</Link>
  </div>
</nav>

<style lang="scss">
  nav {
    background: #f8f9facc;
    display: flex;
    flex-direction: row;
    height: 6rem;
    width: 100%;
    padding: 2rem;
    align-items: center;
    position: fixed;
    border-bottom: 1px solid gray;

    :global(a) {
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
  }

  div {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    margin-left: auto;
    padding: 30px;
  }
</style>
