<script>
  import { title } from "../store.js";
  import Card from './../layout/card/Card.svelte';
  import Row from './../layout/Row.svelte';
  import PdfViewer from 'svelte-pdf';

  title.set("Análise de tarefas");
</script>

<PdfViewer url="./assets/pdf/analise-de-tarefas.pdf" />