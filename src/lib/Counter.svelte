<script>
  let count = $state(0);
</script>

<button
  onclick={() => count++}
  class="p-4 mt-12 border border-indigo-900 border-opacity-80 rounded-md hover:border-indigo-500 hover:bg-slate-800 transition-all duration-300"
>
  count is {count}
</button>
