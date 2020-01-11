<script>
  import Hello from './components/Hello.svelte';
  const name = "skirmisher";
</script>

<style lang="scss">
  @import "./styles/variables.scss";

  .App {
    height: 100%;
    width: 100%;
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    background: $light-primary;
  }
</style>

<div class="App">
  <Hello {name} />
</div>
