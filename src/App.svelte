<script>
  import Button from './lib/Buttons/Button.svelte';
  let count = $state(0);
  const increment = () => count += 1;
</script>

<Button mode="light" onClick={() => increment()}>Count: {count}</Button>