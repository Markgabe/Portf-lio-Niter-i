<script>
  import PieChart from '../components/chart/PieChart.svelte';
  import BarChart from '../components/chart/BarChart.svelte';
  import ColumnChart from '../components/chart/ColumnChart.svelte';
</script>
 
<PieChart 
  title = 'Idade'
  labels = {['Entre 18 e 25', 'Entre 26 e 35', 'Entre 36 e 45', 'Entre 46 e 59', 'Acima de 59']}
  series = {[5, 3, 0, 1, 1]}
/>

<PieChart
  title = 'Gênero'
  labels = {['Masculino', 'Feminino', 'Prefiro não dizer']}
  series = {[6, 4, 0]}
/>

<BarChart 
  title = 'Ocupação'
  labels = {['Estudante', 'Médico', 'Advogada', 'Analista', 'Biomédica']}
  series = {[5, 1, 1, 1, 1]}
/>

<PieChart 
  title = 'Necessidade especial'
  labels = {['Sim', 'Não']}
  series = {[0, 10]}
/>

<BarChart 
  title = 'Familiaridades'
  labels = {['Smartphone ou Tablet', 'Notebook ou Computador de Mesa', 'Televisão']}
  series = {[10, 6, 0]}
/>

<ColumnChart
  title = 'Frequência de uso'
  labels = {['Facebook', 'Instagram', 'Whatsapp', 'Youtube', 'Sites de notícias', 'Sites governamentais']}
  series = {[
    {
      name: 'Nunca usei',
      data: [0, 0, 0, 0, 0, 1]
    }, {
      name: 'Usei poucas vezes',
      data: [4, 3, 0, 2, 3, 7]
    }, {
      name: 'Uso às vezes',
      data: [4, 2, 3, 2, 6, 2]
    }, {
      name: 'Uso regularmente',
      data: [2, 5, 7, 6, 1, 0]
    }
  ]}
/>

<PieChart 
  title = 'Já utilizou o site da prefeitura?'
  labels = {['Sim', 'Não']}
  series = {[6, 4]}
/>

<PieChart 
  title = 'Já buscou notícias no site da prefeitura?'
  labels = {['Sim', 'Não']}
  series = {[3, 1]}
/>