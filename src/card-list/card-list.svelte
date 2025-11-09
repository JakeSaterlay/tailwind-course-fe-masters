<script lang="ts">
  import Card from '../card/card.svelte';
  import PrimaryButton from '../button/primary-button.svelte';
</script>

<div class="flex items-center gap-2">
  <div>
    <input type="checkbox" />
  </div>
  <div>
    <h2>Unsubscribe</h2>
    <PrimaryButton />
  </div>
</div>

<div class="flex flex-col gap-4 md:flex-row">
  <Card title="Card Title" description="This is a description of the card." />
  <Card title="Another Card" description="This is another description of a different card." />
  <Card title="Third Card" description="This is a description of the third card." />
  <Card title="Fourth Card" description="This is a description of the fourth card." />
</div>
