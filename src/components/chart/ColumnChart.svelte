<script>
  import { chart } from "svelte-apexcharts";
  export let title;
  export let labels;
  export let series;

  var options = {
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
      type: 'bar',
      height: 350,
      width: 500,
      toolbar: {
        show: false
      }
    },
    plotOptions: {
      bar: {
        horizontal: false,
        columnWidth: '55%',
        endingShape: 'rounded'
      },
    },
    dataLabels: {
      enabled: false
    },
    stroke: {
      show: true,
      width: 2,
      colors: ['transparent']
    },
    xaxis: {
      categories: labels,
    },
    fill: {
      opacity: 1
    },
  };
</script>
 
<div use:chart={options} />