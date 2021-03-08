<script>
  import { title } from "../store.js";

  title.set("Metas de Design");
</script>

<article>
  <p>
    Visando a melhoria mais ágil do site da prefeitura, buscamos por possíveis
    melhoras baseadas em seu impacto comparado ao esforço necessário para a
    implementação.<br />
    Buscamos respeitar sempre os fundamentos de Web Design. Sabendo que esses fundamentos,
    quando aplicados, aumentam drasticamente a qualidade para a interação do usuário.
  </p>

  <h2>
    Para este tipo de site, algumas prioridades específicas são consideradas:
  </h2>
  <h3>Acessibilidade</h3>
  <p>
    A acessibilidade é imprescindível em sites governamentais, visto que é
    necessário que todos os públicos possam utilizá-los.
  </p>
  <hr />
  <h3>Responsividade</h3>
  <p>
    Um design responsivo é importante em muitos websites diferentes. Tanto para
    o conforto do usuário, que muitas prefere a praticidade de plataformas
    mobile, quanto para que usuários que não possuam um computador ainda possam
    utilizar o site.
  </p>
  <hr />
</article>

<style lang="scss">
  h2,
  h3 {
    align-self: flex-start;
    margin: 30px 0;
  }

  p {
    align-self: flex-start;
    margin-bottom: 30px;
  }
</style>
