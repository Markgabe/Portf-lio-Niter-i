<script>
  import { title } from "../store.js";
  import Print from "../components/analise/Print.svelte";

  title.set("Análise Competitiva");
</script>

<article>
  <h2>Categorização de Serviços</h2>
  <p>
    Como muitos sites governamentais incluem uma grande quantidade de serviços
    prestados, não é possível simplesmente colocá-los na tela sem algum tipo" de
    organização. A única exceção à essa regra nas nossas procuras é o site de
    Curitiba, que conta com uma barra de pesquisa capaz de encontrar serviços,
    ao invés de somente notícias.
  </p>
</article>
<hr />
<article>
  <h2>Responsividade</h2>
  <p>
    Dos exemplos, o único que aprensentou problemas na responsividade foi o de
    São Paulo. Mesmo assim, a navegação num smartphone ainda será muito melhor
    do que no site de Niterói, que não tem nenhuma mudança de layout para telas
    menores.
  </p>
</article>
<hr />
<article>
  <h2>Acessibilidade</h2>
  <p>
    Todos os exemplos, diferentemente do site de Niterói, incluem opções de
    acessibilidade, porém alguns mais do que outros. Teresópolis traz opções de
    contraste, tamanho de fonte, libras e outras opções, enquanto que são paulo
    só inclui atributos para leitores de tela. Mais uma vez aqui Niterói deixa a
    desejar, sem apresentar nenhuma facilitação para esses públicos.
  </p>
</article>
<hr />
<h1>Exemplos utilizados</h1>
<h2>Rio de Janeiro</h2>
<section>
  <Print
    src="./assets/img/rio-servicos.jpg"
    alt="serviços"
    desc="Navegação com serviços categorizados"
  />

  <Print
    src="./assets/img/rio-icones.jpg"
    alt="ícones"
    desc="Grandes ícones para os principais serviços"
  />

  <Print
    src="./assets/img/rio-responsivo.jpg"
    alt="responsividade"
    desc="Responsivo"
  />

  <Print
    src="./assets/img/rio-acessibilidade.jpg"
    alt="acessibilidade"
    desc="Poucos recursos de acessibilidade"
  />
</section>
<hr />
<h2>Teresópolis</h2>
<section>
  <Print
    src="./assets/img/teresopolis-servicos.jpg"
    alt="serviços"
    desc="Navegação com serviços categorizados"
  />

  <Print
    src="./assets/img/teresopolis-icones.jpg"
    alt="ícones"
    desc="Grandes ícones para os principais serviços"
  />

  <Print
    src="./assets/img/teresopolis-responsivo.jpg"
    alt="responsividade"
    desc="Responsivo"
  />

  <Print
    src="./assets/img/teresopolis-acessibilidade.jpg"
    alt="acessibilidade"
    desc="Muitos recursos de acessibilidade"
  />
</section>
<hr />
<h2>Curitiba</h2>
<section>
  <Print
    src="./assets/img/curitiba-hero.jpg"
    alt="hero"
    desc="Hero com call to action para pesquisa"
  />
  <Print
    src="./assets/img/curitiba-responsividade.jpg"
    alt="responsividade"
    desc="Responsivo"
  />
  <Print
    src="./assets/img/curitiba-acessibilidade.jpg"
    alt="acessibilidade"
    desc="Alguns recursos de acessibilidade"
  />
</section>
<hr />
<h2>São Paulo</h2>
<section>
  <Print
    src="./assets/img/sao-paulo-servicos.jpg"
    alt="serviços"
    desc="Navegação com serviços categorizados"
  />
  <Print
    src="./assets/img/sao-paulo-responsividade.jpg"
    alt="responsividade"
    desc="Dificuldades na responsividade"
  />
  <Print
    src="./assets/img/sao-paulo-acessibilidade.jpg"
    alt="acessibilidade"
    desc="Poucos recursos de acessibilidade"
  />
</section>
<hr />

<style lang="scss">
  article {
    display: flex;
    flex-direction: column;

    p {
      margin: 40px 0;
    }
  }
  section {
    margin: 40px auto;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, auto));
    column-count: 2;
    gap: 5rem;
    justify-content: space-around;
    padding: 0 70px;
    width: 100%;
  }

  p {
    margin-top: 10px;
    font-weight: bold;
  }

  h1,
  h2 {
    margin-top: 25px;
    align-self: flex-start;
  }
</style>
