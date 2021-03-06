<script>
  export let title;
  export let text;
</script>

<div>
  <h1>
    {title}
  </h1>

  <p class="hyphenate">
    {@html text}
  </p>
</div>

<style lang="scss">
  div {
    padding: 10px 20px;
    word-break: keep-all;
    flex-grow: 1;
    flex-basis: 0;
    background: transparent;
    margin: 0 10px;

    p {
      margin-top: 10px;
      hyphens: auto;
    }
  }
</style>
