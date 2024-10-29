<script>
  import Button from './lib/Buttons/Button.svelte';
  import WideButton from './lib/Buttons/WideButton.svelte';
  let count = $state(0);
  const increment = () => count += 1;
</script>

<Button mode="light" onClick={() => increment()}>Count: {count}</Button>
<div style="width: 10rem;"><WideButton mode="light" onClick={() => increment()}>Count: {count}</WideButton></div>