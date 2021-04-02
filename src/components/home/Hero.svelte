<form action="/" method="get">
  <input
    type="search"
    placeholder="O que procura?"
    aria-label="Search"
    name="query"
  />
  <button type="submit">Pesquisar</button>
</form>

<style lang="scss">
  form {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 50rem;
    background: url("../assets/img/hero-img.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 100% 80%;
  }

  input {
    width: 70em;
    height: 3em;
    border-radius: 1.5em;
    padding: 1em 2em;
    background: #fffd;
    border: 3px solid #fffd;
    transition: all 0.2s;

    &:focus {
      border-color: #d16721;
    }
  }

  button {
    margin: 15px;
    height: 2.7em;
    width: 12em;
    border-radius: 1.5em;
    border: 0;
    font-size: 1.2rem;
    font-weight: bold;
    background: #d16721;
    color: #fff;
    cursor: pointer;

    transition: all 0.2s;

    &:hover {
      background: #ff7c26;
    }
  }
</style>
