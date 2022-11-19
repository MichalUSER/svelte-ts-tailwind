<script lang="ts">
  import Counter from "./lib/Counter.svelte";
</script>

<div class="flex h-screen items-center justify-center flex-col">
  <Counter />
</div>

<style>
  :global(body) {
    @apply bg-gray-900;
  }
</style>
