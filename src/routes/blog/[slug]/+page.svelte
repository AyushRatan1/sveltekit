<script lang="ts">
    export let data;
</script>

<div>
  {#each data.cart as { name } (name)}
    <div class="font-semibold">{name}</div>
  {/each}
</div>