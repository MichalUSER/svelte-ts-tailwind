<script lang="ts">
  let counter = 0;

  function increase() {
    counter += 1;
  }
</script>

<button class="text-indigo-300 border-2 rounded border-slate-600 px-3 py-2 focus:bg-gray-800" on:click={increase}>Count: {counter}</button>
