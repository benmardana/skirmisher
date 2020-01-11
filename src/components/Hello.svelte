<script>
  export let name;
</script>

<style lang="scss">
  @import "../styles/variables.scss";

  .Hello {
    text-align: center;
    font-size: 6em;
    background-color: $red-primary;
    color: $grey-primary;
    margin: 10px;
    padding: 10px;
    border-radius: 10px;
  }
</style>


<div class="Hello">
  Hello, { name }!
</div>
