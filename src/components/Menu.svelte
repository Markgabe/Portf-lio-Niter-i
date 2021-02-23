<script>
    import Toggl from "./Toggl.svelte";
</script>

<nav class='navbar navbar-dark bg-dark sticky-top'>
    <a class="navbar-brand" href="">
        <img src="../../assets/img/logo-4.png" alt="Logo">
    </a>
    <ul class='navbar-nav'>
        <li class='nav-item active'>
            <a href="" class='nav-link'>Home</a>
        </li>
        <li class='nav-item'>
            <a href="" class='nav-link'>Pesquisa Desk</a>
        </li>
        <li class='nav-item'>
            <a href="" class='nav-link'>Personas</a>
        </li>
    </ul>

    <form class="form ms-auto me-2 d-flex row align-items-center w-50">
      <!-- bate papo uol
            mark-69-cm: foi
      -->
      <div class="ms-auto col-9">
        <input class="form-control" type="search" placeholder="O que procura?" aria-label="Search">
      </div>
      <div class="col-1">
        <button class="btn btn-outline-light mx-1" type="submit">Search</button>
      </div>
      <div class="col-1">
          <Toggl />
      </div>
    </form>
    
</nav>

<style>

    button {
      color: #d16721;
      background: #fff;
      font-weight: bold;
      border-color: #d16721;
      border-radius: 10px;
      transition: color 0.2s, background 0.2s;
    }

    button:hover {
      background: #d16721;
      color: #fff;
      border-color: #fff;
    }

    input::placeholder {
        font-weight: bolder;
    }

    nav {
        background-color: #d16721 !important;
    }

    ul {
        display: flex;
        flex-direction: row;
        align-items: center;
    }

    li {
        padding: 0 30px;
    }

    li > a {
        padding: 8px 15px;
        background: transparent;
        color: white !important;
        font-weight: bold;
        text-align: center;
        border: 1px solid white;
        border-radius: 10px;
    }

    li > a:hover {
        background: white;
        color: #d16721 !important;
        border: 1px solid #d16721;
    }

    a:hover {
        text-decoration: none;
    }

    form {
      margin-right: 100px;
    }

    img {
        height: auto;
        width: 200px;
    }

</style>