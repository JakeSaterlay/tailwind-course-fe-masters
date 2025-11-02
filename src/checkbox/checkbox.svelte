<script>
  const { label = 'A Very Important Checkbox', id = 'checkbox', ...props } = $props();
</script>

<div class="rounded border bg-slate-200 p-4 has-[input:checked]:bg-green-200">
  <input class="peer accent-purple-400" {id} {...props} type="checkbox" />
  <label class="peer-checked:line-through" for={id}>{label}</label>
</div>
