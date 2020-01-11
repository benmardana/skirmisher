<script>
  import HelloWorld from './components/HelloWorld.svelte';
</script>

<style lang="scss">
  @import "./styles/colors.scss";

  .App {
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background: $light-primary;
  }
  
</style>

<div class="App">
  <HelloWorld />
</div>
