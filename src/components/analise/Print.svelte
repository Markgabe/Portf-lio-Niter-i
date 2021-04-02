<script>
  export let src, alt, desc;
</script>

<div>
  <img {src} {alt} />
  <p>{desc}</p>
</div>

<style>
  div {
    border-radius: 15px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 10px;
  }

  img {
    width: 100%;
    object-fit: contain;
  }

  p {
    font-size: 1rem;
    margin-top: 5px;
    font-weight: bold;
    color: #333;
  }
</style>
