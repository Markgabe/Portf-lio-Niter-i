<script>
  import { Link } from "svelte-routing";
  import {
    Collapse,
    Navbar,
    NavbarToggler,
    NavbarBrand,
    Nav,
    UncontrolledDropdown,
    DropdownToggle,
    DropdownMenu,
    DropdownItem
  } from 'sveltestrap';

  let isOpen = false;

  function handleUpdate(event) {
    isOpen = event.detail.isOpen;
  }
</script>

<Navbar color="light" light expand="md">
  <NavbarBrand href="/">Portfólio</NavbarBrand>
  <NavbarToggler on:click={() => (isOpen = !isOpen)} />
  <Collapse {isOpen} navbar expand="md" on:update={handleUpdate}>
    <Nav class="ml-auto" navbar>
      <UncontrolledDropdown nav inNavbar>
        <DropdownToggle nav caret>Análise</DropdownToggle>
        <DropdownMenu right>
          <DropdownItem>
            <Link to="/analise" class="nav-link">Análise Competitiva</Link>
          </DropdownItem>
          <DropdownItem>
            <Link to="/brainstorm" class="nav-link">Brainstorm</Link>
          </DropdownItem>
          <DropdownItem>
            <Link to="/desk" class="nav-link">Pesquisa Desk</Link>
          </DropdownItem>
          <DropdownItem>
            <Link to="/form" class="nav-link">Questionário</Link>
          </DropdownItem>
          <DropdownItem>
            <Link to="/results" class="nav-link">Resultados do questionário</Link>
          </DropdownItem>
        </DropdownMenu>
      </UncontrolledDropdown>
      <UncontrolledDropdown nav inNavbar>
        <DropdownToggle nav caret>Prototipação</DropdownToggle>
        <DropdownMenu right>
          <DropdownItem>
            <Link to="/personas" class="nav-link">Personas</Link>
          </DropdownItem>
          <DropdownItem>
            <Link to="/sorting" class="nav-link">Card Sorting</Link>
          </DropdownItem>
          <DropdownItem>
            <Link to="/cenarios" class="nav-link">Cenários de uso</Link>
          </DropdownItem>
        </DropdownMenu>
      </UncontrolledDropdown>
    </Nav>
  </Collapse>
</Navbar>