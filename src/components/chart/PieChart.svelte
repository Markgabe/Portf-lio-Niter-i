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
    series: series,
    chart: {
    width: 380,
    type: 'pie',
    },
    labels: labels,

    responsive: [{
      breakpoint: 480,
      options: {
        chart: {
          width: 200
        },
        legend: {
          position: 'bottom'
        }
      }
    }]
  };
</script>
 
<div use:chart={options} />