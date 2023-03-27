<script lang="ts">
  import Card from "./card.svelte";
</script>

<div class="one_col">
  <Card />
</div>
<div class="two_col">
  <div>
    <Card />
    <Card />
    <Card />
  </div>
  <div>
    <Card />
    <Card />
    <Card />
  </div>
</div>

<style>
  .two_col {
    display: flex;
  }

  .two_col div {
    width: 100%;
  }
</style>
