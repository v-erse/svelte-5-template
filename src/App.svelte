<script lang="ts">
  let count = $state(0);
</script>

<button onclick={() => count++}>
  clicks: {count}
</button>
