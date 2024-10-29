<script>
    let { name, mode, onClick, className, style, edging } = $props();
</script>
<svelte:head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/definiteconfusion/notion-components/src/notion-components/Buttons/Buttons.css">
</svelte:head>

<button class={`button-main max-button-width ${mode} ${className}`} onclick={onClick} style={`margin-inline:${edging};${style}`} >
    <slot></slot>
</button>