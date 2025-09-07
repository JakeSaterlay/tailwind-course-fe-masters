<script>
  const { title = 'Card Title', description = '' } = $props();
</script>

<div class="rounded-md border-2 border-slate-200 bg-white p-4 shadow-sm">
  <h2 class="text-2xl font-semibold">{title}</h2>
  <p class="mt-1">{description}</p>
</div>
