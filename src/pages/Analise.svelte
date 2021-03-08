<script>
  import { title } from "../store.js";

  title.set("Análise Competitiva");
</script>

<div id="main-section">
  <h1>Análise Competitiva</h1>
  <div id="content">
    <section>
      <h2>Rio de Janeiro</h2>
      <p>
        Navegação com serviços categorizados por prefeitura, turismo, cidadão,
        servidor, empresa e ouvidoria
      </p>
      <img src="./assets/img/rio-servicos.jpg" alt="serviços" />
      <p>Grandes ícones para os principais serviços</p>
      <img src="./assets/img/rio-icones.jpg" alt="ícones" />
      <p>Responsivo</p>
      <img src="./assets/img/rio-responsivo.jpg" alt="responsividade" />
      <p>Poucos recursos de acessibilidade</p>
      <img src="./assets/img/rio-acessibilidade.jpg" alt="acessibilidade" />
    </section>
    <section>
      <h2>Teresópolis</h2>
      <p>
        Navegação com serviços categorizados por cidadão, empreendedor,
        estrutura, servidor e imprensa
      </p>
      <img src="./assets/img/teresopolis-servicos.jpg" alt="serviços" />
      <p>Grandes ícones para os principais serviços</p>
      <img src="./assets/img/teresopolis-icones.jpg" alt="ícones" />
      <p>Responsivo</p>
      <img src="./assets/img/teresopolis-responsivo.jpg" alt="responsividade" />
      <p>Muitos recursos de acessibilidade</p>
      <img
        src="./assets/img/teresopolis-acessibilidade.jpg"
        alt="acessibilidade"
      />
    </section>
    <section>
      <h2>Curitiba</h2>
      <p>Hero com call to action para pesquisa de serviços</p>
      <img src="./assets/img/curitiba-hero.jpg" alt="hero" />
      <p>Responsivo</p>
      <img
        src="./assets/img/curitiba-responsividade.jpg"
        alt="responsividade"
      />
      <p>Alguns recursos de acessibilidade</p>
      <img
        src="./assets/img/curitiba-acessibilidade.jpg"
        alt="acessibilidade"
      />
    </section>
    <section>
      <h2>São Paulo</h2>
      <p>Navegação com serviços categorizados por cidadão, empresa e turista</p>
      <img src="./assets/img/sao-paulo-servicos.jpg" alt="serviços" />
      <p>Dificuldades na responsividade</p>
      <img
        src="./assets/img/sao-paulo-responsividade.jpg"
        alt="responsividade"
      />
      <p>Poucos recursos de acessibilidade</p>
      <img
        src="./assets/img/sao-paulo-acessibilidade.jpg"
        alt="acessibilidade"
      />
    </section>

    <section>
      <h2>Categorização de Serviços</h2>
      <p>
        Como muitos sites governamentais incluem uma grande quantidade de
        serviços prestados, não é possível simplesmente colocá-los na tela sem
        algum tipo" de organização. A única exceção à essa regra nas nossas
        procuras é o site de Curitiba, que conta com uma barra de pesquisa capaz
        de encontrar serviços, ao invés de somente notícias.
      </p>
    </section>
    <section>
      <h2>Responsividade</h2>
      <p>
        Dos exemplos, o único que aprensentou problemas na responsividade foi o
        de São Paulo. Mesmo assim, a navegação num smartphone ainda será muito
        melhor do que no site de Niterói, que não tem nenhuma mudança de layout
        para telas menores.
      </p>
    </section>
    <section>
      <h2>Acessibilidade</h2>
      <p>
        Todos os exemplos, diferentemente do site de Niterói, incluem opções de
        acessibilidade, porém alguns mais do que outros. Teresópolis traz opções
        de contraste, tamanho de fonte, libras e outras opções, enquanto que são
        paulo só inclui atributos para leitores de tela. Mais uma vez aqui
        Niterói deixa a desejar, sem apresentar nenhuma facilitação para esses
        públicos.
      </p>
    </section>
  </div>
</div>

<style>
  #main-section {
    padding: 0 20px;
  }

  #content {
    display: flex;
    flex-wrap: wrap;
  }

  img {
    object-fit: contain;
    width: 100%;
  }

  section {
    width: 50%;
    box-sizing: border-box;
    padding: 0 20px;
  }

  p {
    margin-top: 10px;
    font-weight: bold;
  }

  h2 {
    margin-top: 25px;
  }
</style>
