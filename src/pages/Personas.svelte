<script>
  import { title } from "../store.js";
  import Card from "../layout/card/Card.svelte"

  title.set("Personas");
</script>

<div>
  <Card
    title="Letícia Nunes"
    text="Persona baseada em respostas de mulheres entre 25 e 40 anos em nosso questionário"
  />
  <img src="./assets/img/Leticia_Nunes.png" alt="Letícia Nunes">

  <Card 
    title="Gilson Alves"
    text="Persona baseada em respostas de homens com mais de 40 anos em nosso questionário"
  />
  <img src="./assets/img/Gilson_Alves.png" alt="Gilson Alves">

  <Card
    title="Erick Rocha"
    text="Persona baseada em respostas de homens entre 18 e 30 anos em nosso questionário"
  />
  <img src="./assets/img/Erick_Rocha.png" alt="Erick Rocha">
</div>

<style>
  img {
    width: 100vw;
    max-width: 1366px;
    margin-bottom: 30px;
  }
</style>