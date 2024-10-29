<script>
    let { name, mode, onClick, className, style } = $props();
</script>
<svelte:head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/definiteconfusion/notion-components/src/notion-components/Buttons/Buttons.css">
</svelte:head>

<button class={`button-main ${mode} ${className}`} onclick={onClick} style={style} >
    <slot></slot>
</button>