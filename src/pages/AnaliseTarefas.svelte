<script>
  import { title } from "../store.js";
  import Card from './../layout/card/Card.svelte';
  import Row from './../layout/Row.svelte';
  import PdfViewer from 'svelte-pdf';

  title.set("Análise de tarefas");
</script>

<!--
<Row>
  <Card
    title="Objetivo, Tarefas, Sub-Tarefas"
    text="
    <ul>
      <li>1. Acessar página inicial do site</li>
      <li>2. Buscar serviço
        <ul>
          <li>2.1. Procurar nos mais acessados ou buscar na barra de pesquisa</li>
          <li>2.2. Identificar serviço requisitado</li>
          <li>2.3. Abrir página do serviço</li>
        </ul>
      </li>
      <li>3. Realizar consulta ou serviço
        <ul>
          <li>3.1. Ler instruções</li>
          <li>3.2. Preencher informações solicitadas</li>
          <li>3.3. Prosseguir segundo serviço solicita</li>
          <li>3.4. Verificar dados e imprimir</li>
        </ul>
      </li>
    </ul>"
  />
  <Card
    title="Plano 1"
    text="Fazer 1-2-3-4-5.1-6"
  />
</Row>-->
<PdfViewer url="./assets/pdf/cenarios-de-uso.pdf" />