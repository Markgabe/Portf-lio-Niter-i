<script>
  import { title } from "../store.js";
  import PdfViewer from 'svelte-pdf';

  title.set("Cenários de uso");
</script>

<PdfViewer 
  url="./assets/pdf/cenarios-de-uso.pdf" 
  showBorder={false}  
/>