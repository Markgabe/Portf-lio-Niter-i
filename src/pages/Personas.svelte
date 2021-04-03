<script>
  import { title } from "../store.js";
  import Card from "../layout/card/Card.svelte";

  title.set("Personas");
</script>

<div>
  <Card 
    title=""
    text="Nessa seção, tentamos representar o público que participou da nossa fase de análise. Tanto na pesquisa, quanto no brainstorm, quanto na entrevista.<br>
    <br>Utilizamos as personas como forma de materializar o grupo que utilizará o novo design, de forma que conseguimos nos basear também nas personas como forma de 
    identificar problemas e reelaborar fluxos que se adequem às necessidades das mesmas."
  />

  <hr>

  <Card
    title="Letícia Nunes"
    text="Persona baseada em respostas de mulheres entre 26 e 35 anos e que necessitam de ferramentas para empreendedores.
    Representa o grupo de empreendedores que de alguma forma precisam consultar documentos pelo site da prefeitura, 
    costuma utilizar tanto smartphone como notebook para acessar os serviços e precisa conseguir concluir o fluxo em ambos designs."
  />
  <img src="./assets/img/letNunes.png" alt="Letícia Nunes" />

  <hr>

  <Card
    title="Gilson Alves"
    text="Persona baseada em respostas de homens com mais de 59 anos, que necessitam de maior acessibilidade, 
    tem dificuldades com tecnologia em geral e preferem a utilização do smartphone."
  />
  <img src="./assets/img/gilAlves.png" alt="Gilson Alves" />

  <hr>

  <Card
    title="Erick Rocha"
    text="Persona baseada em respostas de homens entre 18 e 25 anos e que realizam pesquisas para fins de imprensa. 
    Representa o grupo de pessoas que utilizam o site para buscar informações gerais sobre a cidade, não possuem necessidades de acessibilidade, 
    e costumam acessar o site via notebook."
  />
  <img src="./assets/img/eriRocha.png" alt="Erick Rocha" />
</div>

<style>
  img {
    width: 100vw;
    max-width: 1366px;
    margin-bottom: 30px;
  }
</style>
