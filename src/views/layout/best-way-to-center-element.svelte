<script lang="ts">
  import svelteLogo from '../../assets/svelte.svg'
  import Counter from '../../lib/Counter.svelte'
</script>

<main>
  <div class="g-container">
    <div class="g-box"></div>
  </div>
</main>

<style>
  .g-container {
    width: 100vw;
    height: 100vh;

    dispaly: flex;
  }

  .g-box {
    width: 40vmin;
    height: 40vmin;
    background: #000;
    margin: auto;
  }
</style>