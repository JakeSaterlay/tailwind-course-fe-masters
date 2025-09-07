<script>
  const { label = 'Button', ...props } = $props();
</script>

<button
  class="rounded-md bg-white px-4 py-1.5 shadow-sm outline outline-slate-600 hover:bg-slate-100"
  {...props}>{label}</button
>
