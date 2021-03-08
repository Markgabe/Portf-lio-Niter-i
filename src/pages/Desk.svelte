<script>
  import { title } from "../store.js";

  title.set("Desk Research");
</script>

<h1>Desk Research</h1>
<section>
  <div>
    <h2>Navegação</h2>
    <p>
      Um dos principais problemas enfrentados no site da prefeitura de Niterói e
      de websites semelhantes é o de organizar uma grande quantidade de serviços
      disponibilizados.
    </p>
  </div>
  <img src="./assets/img/pexels-leah-kelley-3935702.jpg" alt="navegação" />
</section>
<hr />
<section>
  <img src="./assets/img/pexels-icsa-1708936.jpg" alt="públicos-alvo" />
  <div>
    <h2>Públicos-alvo</h2>
    <p>
      Porém, os serviços providos pelo site, muitas vezes, não tem um mesmo
      público-alvo. Várias opções são direcionadas a cidadãos, empreendedores,
      turistas, servidores ou imprensa. Por exemplo, a um turista pouco
      interessaria informações sobre IPTU. Portanto, opções como essa só
      serviriam para ocupar espaço na tela do usuário.
    </p>
  </div>
</section>
<hr />
<section>
  <div>
    <h2>Acessibilidade</h2>
    <p>
      Acessibilidade é necessária em sites governamentais, considerando que
      todos devem ser capazes de utilizá-los sem maiores problemas.
    </p>
  </div>
  <img src="./assets/img/pexels-cottonbro-6321231.jpg" alt="acessibilidade" />
</section>
<hr />
<section>
  <img
    src="./assets/img/pexels-negative-space-34140.jpg"
    alt="responsividade"
  />
  <div>
    <h2>Responsividade</h2>
    <p>
      Responsividade é uma funcionalidade necessária nos dias de hoje, contando
      que muitos usuários preferem a conveniência do uso do celular, ou não
      possuem um computador em casa.
    </p>
  </div>
</section>
<hr />
<section>
  <div>
    <h2>Artigos</h2>
    <p>
      A presença de artigos e postagens é muito usada em sites desse tipo.
      Porém, com a predominância das redes sociais, muitas dessas postagens são
      feitas tanto no site quanto no Facebook, Twitter, etc. Tornando muitas
      dessas notícias redundantes.
    </p>
  </div>
  <img src="./assets/img/pexels-gabby-k-6237910.jpg" alt="artigos" />
</section>

<style>
  section {
    margin: 0 auto;
    display: flex;
    justify-content: space-around;
    padding: 70px;
  }

  hr {
    border-top: 1px solid rgba(0, 0, 0, 0.1);
    border-bottom: 1px solid rgba(255, 255, 255, 0.3);
    width: 65%;
    margin: 0 auto;
  }
  p {
    margin: 40px 0;
  }

  img {
    width: 30%;
    object-fit: contain;
  }

  div {
    width: 30%;
    padding: 10px;
  }
</style>
