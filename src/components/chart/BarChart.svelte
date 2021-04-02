<script>
  import { chart } from "svelte-apexcharts";
  export let title;
  export let labels;
  export let series;
  
  let options = {
    title: {
      text: title,
      align: 'center',
      margin: 20,
      style: {
        fontSize:  '14px',
        fontWeight:  'bold',
        color:  '#263238'
      },
    },
    series: [{
      data: series
    }],
    chart: {
      width: 350,
      type: 'bar',
      toolbar: {
        show: false
      }
    },
    plotOptions: {
      bar: {
        borderRadius: 4,
        horizontal: true,
      }
    },
    xaxis: {
      categories: labels
    },
    
  };
</script>
 
<div use:chart={options} />