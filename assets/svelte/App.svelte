<script>
    import { onMount } from 'svelte';

    onMount(() => {
        console.log(`Symfony + Svelte`);
    });
</script>


<style>
    .component-wrapper {
        border: 2px dotted #333;
        padding: 1rem;
    }
    h1 {
        font-family: sans-serif;
        color: #222;
        text-align: center;
    }
    p {
        color: #444;
        text-align: center;
    }
</style>


<div class="component-wrapper">
    <h1>Symfony + Svelte</h1>
    <p>This is App.svelte component</p>
</div>
