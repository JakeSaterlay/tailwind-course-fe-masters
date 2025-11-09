{#snippet link(title)}
  <li class="group border-b-4 hover:bg-red-200">
    <a href="#" class="p-2">{title}</a>
  </li>
{/snippet}

<nav class="flex justify-between">
  <a class="text-xl font-extrabold" href="/">Unicorn Corp</a>
  <ul class="flex gap-4">
    {@render link('Home')}
    {@render link('About')}
    {@render link('Services')}
    {@render link('Contact')}
  </ul>
</nav>

<div class="flex gap-2">
  <div class="bg-purple-500">1</div>
  <div class="bg-purple-500">2</div>
  <div class="bg-purple-500">3</div>
</div>
